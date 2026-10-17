# RFP Writing Style

How every RFP in this workspace must read. The goal: a document a vendor can
bid against without guessing, and an evaluation committee can score fairly.

## Voice
- **Clear and neutral.** Plain, professional language. No marketing tone, no
  filler, no hedging. The reader is a busy vendor pricing a bid.
- **Active and direct.** "The vendor shall provide…" not "It would be good
  if a vendor could possibly…".
- **Consistent terms.** Pick one word for a thing and keep it (don't switch
  between "supplier", "vendor", "contractor" at random — choose one).

## Requirements must be specific, measurable, testable
- Quantify everything you can: numbers, capacities, dimensions, durations,
  response times, quantities. "Fast Wi-Fi" → "≥ 50 Mbps sustained per 100
  concurrent users".
- Every requirement pairs with an **acceptance criterion** — how you'll know
  it's met.
- Mark each requirement **Mandatory (M)** or **Desirable (D)**. Don't make
  everything mandatory; over-specifying kills competition and inflates price.
- Don't describe the *solution* when you mean the *outcome*. State the
  result you need and let vendors propose how — unless a specific method is
  genuinely required.

## Structure
- Number every section and requirement so they can be referenced in Q&A and
  scoring (e.g. "re: 4.7").
- Use tables for requirements, deliverables, evaluation weights, and pricing.
- Keep sections in the template order so vendors and committees know where to
  look.

## Honesty & sourcing
- Never invent figures, vendor names, standards, or dates. If a fact is
  missing, write `[TODO: …]` and ask — don't paper over it.
- When a requirement is based on a standard or benchmark, name the standard
  precisely (number/version) and make sure it's backed by something in the
  RFP's `research/` folder with a real source.

## Language (Arabic + English)
- Write in the organization's default language (see the **Organization
  profile** in the root `AGENTS.md`).
- In Arabic text, keep technical terms and acronyms in English inline —
  `RFP`, `SLA`, `KPI`, `VAT`, `AV`, `Wi-Fi` — rather than transliterating.
- Currency is **SAR**; state the VAT treatment explicitly.

## Fairness
- Evaluation weights must sum to 100% and be stated up front.
- Eligibility (pass/fail) is separate from scored criteria.
- Don't write requirements that only one known vendor could meet unless
  there's a documented, legitimate reason.
