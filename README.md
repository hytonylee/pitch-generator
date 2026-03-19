# Pitch Generator Skill

Generate concise, audience-targeted pitch drafts for products, projects, and ideas — with dedicated guidance for pre-seed fundraising.

## What this skill does

This skill helps produce:

- A short "patterns used" note (when benchmark decks are available)
- A one-liner pitch
- A short paragraph pitch
- A concise investment-style pitch

It guides the assistant to ask for missing context (audience, goal, stage, traction, timing, and ask), then returns clear, specific messaging optimized for either live delivery or email.

### Pre-seed stage support

When the user is at the pre-seed stage, the skill automatically adjusts:

- **Inputs**: asks about investor type (friends & family, angel, accelerator, institutional), use of funds / milestone roadmap, and instrument type (SAFE, convertible note).
- **Traction framing**: adds a Tier 5 evidence level for problem validation (customer discovery, waitlists, prototype demos) since most pre-seed companies lack revenue.
- **Pitch priorities**: weights founder-market fit, problem depth, and use-of-funds clarity over financial projections.
- **Investor-type tailoring**: adapts tone and detail level for friends & family vs. angels vs. accelerators vs. institutional pre-seed VCs.
- **Anti-patterns**: flags common pre-seed mistakes like premature financials, stacking confusing SAFE terms, and claiming traction that doesn't exist.
- **Benchmark data**: calibrates asks and framing against typical pre-seed ranges ($250K–$1M, SAFEs, 12–18 month runway targets).

## Benchmark workflow (local-first)

- Local benchmark decks should be placed in `skills/pitch-generator/benchmarks`.
- When benchmark decks exist, the skill should:
  - select the closest benchmark by audience/stage
  - extract 1-2 concrete messaging patterns
  - adapt those patterns to the user's context (without copying claims or wording)
- Prefer local files over external URLs for security and reliability.

Current local benchmark example:

- `skills/pitch-generator/benchmarks/2009_airbnb-pitch_deck.pdf`

## Sources

This skill draws on:

- [Skillsmith Docs](https://www.skillsmith.app/docs) — skill authoring framework
- [Carta: Pre-Seed Funding Guide](https://carta.com/learn/startups/fundraising/pre-seed-funding/) — pre-seed stage definitions, investor types, readiness signals, typical round sizes, instrument guidance (SAFEs / convertible notes), dilution benchmarks, and common fundraising mistakes

## Skill file

- `SKILL.md`
