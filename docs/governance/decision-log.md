# Decision log

> Bootstrap record, 2026-11-07. **No new architecture decision is accepted here.**

## Inherited accepted authority

| Reference | Inherited boundary |
|---|---|
| HTBW DL-131 | Home Steward knowledge product, behind Assist/Concierge, no new responsibility or native-capability regression |
| HTBW DL-81 | Household Knowledge Provider pipeline and governed knowledge use |
| HTBW DL-82 | Source-class provenance, uncertainty and existing Decision Trace ownership |
| HTBW DL-93 | Independent Person Home Steward/General Questions gates; provider selection is not permission |
| HTBW DL-86 | Optional Home Intelligence hosting boundary, distinct from Home Steward |
| HTBW DL-153 | **BehavesWell Framework, Foundation, Core, Edition, and Context Identity** (accepted 2026-11-10, [Core #214](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/214)): six Framework stages over Layer 0 Foundation; BehavesWell Core, Home Assistant Edition; and **BehavesWell Extended Intelligence as the successor product name of the DL-131 product formerly named Home Steward** — one product renamed, not a second product. [ADR](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-behaveswell-framework-foundation-core-edition-and-context-identity.md) |

> **Annotation, 2026-11-10 (DL-153, [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6)).**
> "Home Steward" in the rows above and in the bootstrap record below is the product's former name and
> is not rewritten. The product continues under **BehavesWell Extended Intelligence**, with DL-131's
> boundary unchanged.

## Accepted product identity (inherited from DL-153)

This repository records, without inventing a local decision number, the inherited acceptance of the
successor product identity:

- **BehavesWell Extended Intelligence** is the current canonical name. **Home Steward** is the former
  working/public name. No second product entry exists.
- References: **DL-131** (product boundary, unchanged) and **DL-153** (name and relationship to the
  six-stage Framework, Layer 0 Foundation, and BehavesWell Core).
- "Extended" means a broader explicitly authorized reasoning context, never broader authority.
- Repository-local dispositions (stable technical identifiers retained, source maturity classification,
  © handling, visual-identity constraints) are recorded in
  [product identity and compatibility boundary](../architecture/product-identity-and-compatibility-boundary.md),
  implemented under [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6).

Links and controlling order: [authority order](authority-order.md).

## Owner-directed bootstrap work (not architecture acceptance)

- Public `home_steward` architecture/research baseline with exactly five issues.
- New requirements remain proposed and await Owner acceptance.
- Local-only candidate qualification profile; no amendment of broader DL-93 provider options.
- Separate HTBW README link, no runtime/deployment/platform or hardware choice.
- Organization uses milestones consistently: undated Architecture and Platform Qualification milestone.
- Mixed licensing conventions: no invented license; rights reserved pending explicit decision.

## Proposed / unresolved

Contracts, source dimensions, derived lifecycle and qualification method are a baseline for review,
not accepted mechanics. The public Framework six/seven publication discrepancy was resolved at the
repository level by **DL-153** (six stages over Layer 0 Foundation). Public stage-definition wording
remains open at [Core #215](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/215).
No architecture decision number is invented or existing HTBW decision overwritten.

No vendor is selected, no candidate is qualified, no Owner PASS is recorded, no issue is closed.
