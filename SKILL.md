---
name: pitch-generator
description: >-
  Generate concise, targeted pitch drafts for products, projects, or ideas tailored to a
  target audience. Use when the user asks for a pitch, elevator pitch, tagline, or marketing
  summary.
---

# Pitch Generator

## When to use

Use this skill when the user asks for a pitch for an idea, product, project, or concept—especially for fundraising, partnerships, or customer acquisition.

## Inputs to ask for (if missing)

- Audience: who are we pitching (investor, VC partner, customer, employer, internal leadership)?
- Audience level: generalist vs specialist (how much jargon/data is acceptable)?
- Goal: what should the audience do next (meet you, invest, pilot, buy, hire, refer)?
- Format: live pitch (more visuals/less words) vs emailed message (more words + appendices-ready detail).
- Tone: professional, friendly, bold, etc.
- Problem details (use the “1-sentence test” inputs):
  - Who is affected?
  - Root cause?
  - Impact (cost/risk/time/pain)?
- Value proposition details (use the “solution statement” inputs):
  - Who you help
  - What you do for them
  - Outcome they get
  - Alternative you displace (contrast)
- Proof / traction (use the strongest available evidence):
  - Tier 1: revenue / paying customers
  - Tier 2: signed commitments (LOIs, design partners, pilots)
  - Tier 3: usage/engagement metrics
  - Tier 4: qualitative proof (quotes, NPS, referrals)
- Why now (timing thesis): what has shifted that makes this the right moment?
- Market context (optional, only if the user has it):
  - TAM/SAM/SOM framing or a credible target/customer count within 3 years
- Competition / alternatives (who they compare you to, and are you additive or displacing?)
- Team (optional, only if relevant to the ask):
  - domain expertise, unfair advantage, why you/why now, execution history
- Ask or next step (especially if fundraising):
  - amount, structure, milestones, and timeline (or a concrete “next step” like “request a 30-min meeting”)

## Output format
Return 3 variants, each targeted to the audience and aligned to the workshop structure:

1. **One-liner pitch**
   - Must answer the “three questions to answer cold” in plain language:
     - What do you do?
     - Who is it for?
     - Why does it matter now?
   - No jargon; quantify the benefit if possible.

2. **Short paragraph pitch**
   - Must follow the “story arc”:
     - Tension (problem)
     - Insight (your unfair knowledge / root cause)
     - Resolution (your solution)
     - Proof (the strongest evidence tier you have)
   - Avoid hedging/filler; be direct and confident.

3. **Slightly longer “investment-style” pitch (still concise)**
   - Mirror the “10 essential slides” at the level of messaging (not slide formatting):
     - Problem → Solution → Market → Business model → Traction (proof hierarchy) → GTM → Competition/alternatives → Team → Financials/metrics (only if the user has them) → Ask/next step
   - Include assumptions drivers if financials/market numbers are mentioned (avoid “hockey stick” without drivers).

## Style rules (from the workshop)
- Clarity first: one sentence per core claim; define any necessary terms.
- Specificity wins conviction: name customers (ideally by role/segment), and quantify benefits.
- Contrast matters: explicitly name the alternative and why you’re better (additive vs displacement).
- Evidence hierarchy: if you don't have Tier 1, use Tier 2/3/4—don't omit proof entirely.
- Timing thesis: include “why now” as a concrete shift, not generic optimism.
- No hedging language: avoid “I think maybe,” “sort of,” “hopefully,” “maybe we could…”

## Live vs emailed guidance
- If the user requests a **live pitch**: keep drafts shorter, punchier, and optimized for delivery (fewer sentences; strong opening/closing; emphasis on one key metric).
- If the user requests an **email**: include extra context and appendices-ready detail (e.g., proof tier, market framing, and what you’d share next).

