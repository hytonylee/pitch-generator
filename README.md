# Pitch Generator Skill

Generate concise, audience-targeted pitch drafts for products, projects, and ideas.

## What this skill does

This skill helps produce:

- A short "patterns used" note (when benchmark decks are available)

- A one-liner pitch
- A short paragraph pitch
- A concise investment-style pitch

It guides the assistant to ask for missing context (audience, goal, traction, timing, and ask), then returns clear, specific messaging optimized for either live delivery or email.

## Benchmark workflow (local-first)

- Local benchmark decks should be placed in `skills/pitch-generator/benchmarks`.
- When benchmark decks exist, the skill should:
  - select the closest benchmark by audience/stage
  - extract 1-2 concrete messaging patterns
  - adapt those patterns to the user's context (without copying claims or wording)
- Prefer local files over external URLs for security and reliability.

Current local benchmark example:

- `skills/pitch-generator/benchmarks/2009_airbnb-pitch_deck.pdf`

## Source reference

This skill was created using Skillsmith documentation:

- [Skillsmith Docs](https://www.skillsmith.app/docs)

## Skill file

- `SKILL.md`
