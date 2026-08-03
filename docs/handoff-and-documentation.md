# Handoff and documentation

**Status:** Process note  
**Goal:** Operator receives a **usable map**, not a filing cabinet

## The failure mode

A lease gets signed. Someone says "legal has it." Six months later:

- CAM reconciliation surprises the budget
- HVAC maintenance wasn't on anyone's calendar
- Insurance certificate deadline passed; landlord sends a default notice
- Renewal notice window closes because nobody tracked the date

The contract existed. **Operational memory did not.**

## Handoff bar

Same bar as ServeIT partner site handoffs: the person running the business day-to-day can answer:

1. What do I pay, when, and to whom?
2. What breaks if I miss a date?
3. What maintenance am I responsible for vs. the landlord?
4. Who do I call when something goes wrong?
5. When do I need to decide about renewal or exit?

If they can't answer from your deliverable, the handoff failed — regardless of how thorough the underlying legal review was.

## Recommended deliverable stack (private work product)

Keep these **local** or in client-controlled storage — not in this public repo:

| Artifact | Purpose |
|----------|---------|
| One-page operator summary | Plain language; no legalese hedge maze |
| Payment calendar | Base rent, CAM estimates, known annual true-ups |
| Obligations matrix | Clause → action → owner → frequency |
| Contact sheet | Landlord PM, insurance broker, HVAC vendor, attorney |
| Red-flag memo | Clauses that need counsel or negotiation next round |

## Plain-language rules

1. **Name the trigger** — "If X happens, tenant pays within Y days" beats "pursuant to Section 12."
2. **Use dollars and dates** — ranges only when the lease itself is formula-based.
3. **Separate must-do from nice-to-know** — operators skim under stress.
4. **ELI5 the cross-references** — Section 5(B) feeding Section 8(C) is where people get lost.
5. **No false certainty** — flag "needs attorney confirmation" honestly.

## Documentation hygiene

- Version summaries when amendments arrive
- Date-stamp CAM estimates vs. actual reconciliations
- Log estoppel / SNDA requests — they recur at refinance and sale
- Never mix multiple tenants' materials in one folder without access controls

## Public patterns only here

This repo publishes **generic checklists and process framing**. Client-specific summaries stay out of git — see [CONTRIBUTING.md](../CONTRIBUTING.md).

## Parallel to clinic handoffs

| ServeIT site handoff | Lease handoff |
|----------------------|---------------|
| Staff can update content without a developer | Operator can track obligations without re-reading 40 pages |
| Pre-ship accessibility checklist | Clause review checklist |
| Chunk map / maintainer guide | Obligations matrix |
| Known limitations documented | Aggressive clauses flagged for counsel |

Clinic resources: [serveit-accessibility](https://github.com/zhao-langxi/serveit-accessibility) · [local-digital](https://github.com/zhao-langxi/local-digital).

## See also

- [Clause review checklist](./clause-review-checklist.md)
- [Sibling systems throughline](./sibling-systems-throughline.md)
