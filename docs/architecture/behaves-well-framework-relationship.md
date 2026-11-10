# BehavesWell Framework relationship

> Accepted authority restatement of HTBW **DL-153** (2026-11-10) and **DL-131**; this repository adds no
> Framework or Core architecture. Updated under [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6).
> Governing record: [DL-153 ADR](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-behaveswell-framework-foundation-core-edition-and-context-identity.md).

BehavesWell Extended Intelligence (formerly Home Steward) applies the common BehavesWell governance
discipline. It does not create an AI framework, a Framework stage, or a Core layer. Human Trust is an
outcome, not a component. **It does not implement the six-stage Framework**; BehavesWell Core does.
It may support governed Core capabilities with reasoning or information only through explicit,
authorized contracts.

## The accepted model (DL-153)

- **BehavesWell Framework** — six stages, in order: **1 Truth, 2 Identity, 3 Operational Trust,
  4 Stewardship, 5 Continuity, 6 Concierge.**
- **Foundation** — **Layer 0**: the implementation-platform substrate on which BehavesWell Core applies
  the six stages. **It is not a seventh Framework stage.**
- **BehavesWell Core** — the governed software implementation of the Framework over Layer 0 Foundation,
  forming a seven-layer stack (0 Foundation … 6 Concierge).
- **BehavesWell Core, Home Assistant Edition** — the current and only edition. Home Assistant supplies
  Layer 0 and remains authoritative for its native concepts.
- **Homes That Behave Well** — the residential research, education, and evidence ecosystem.
- **BehavesWell Extended Intelligence** — an **independent** product outside the Core stack.

<a id="accepted-htbw-responsibility-mapping"></a>
## How the product relates to each layer

Each owner below is a BehavesWell Core owner. BehavesWell Extended Intelligence consumes from it only
through governed, authorized interfaces and never becomes its authority.

| Layer | Owner's role | BehavesWell Extended Intelligence |
|---|---|---|
| 0 **Foundation** | Structure, Assets, People, Rooms, relationships, vocabulary, source references, capabilities, consent records | Consumes them; never a competing authority |
| 1 **Truth** | Authoritative current and historical Facts | Retrieval, research, and confident model output never automatically become Truth |
| 2 **Identity** | Effective Person resolution | Data availability is not entitlement |
| 3 **Operational Trust** | Access, disclosure, privacy, consent policy, confirmation, authority, autonomy for this request | Knowledge is never a shortcut around it |
| 4 **Stewardship** | What matters and must be cared for; obligations | Authorized knowledge may enrich an explanation or proposal. The product cannot create, remove, or satisfy an obligation, and it is not Stewardship |
| 5 **Continuity** | Sessions, context, interaction history, experience continuity | May contribute conversation without owning it |
| 6 **Concierge** | Orchestrates appropriate behavior; may invoke the product for an answer, uncertainty, candidate relationship, or proposal | Execution remains governed through BehavesWell Core |

**Behavioral Governance and the Decision Trace** are cross-cutting, with contributions from the
existing owners. The product provides minimal explainable evidence; it requires no indefinite retention
of raw prompts or sources, and it never becomes the Trace owner.

## Publication discrepancy

> **Historical, resolved by DL-153 on 2026-11-10.** Retained so earlier links and the #1 record remain
> truthful.

Public evidence, read 2026-11-07:

- [Framework home](https://behaveswellframework.com/) describes "six framework layers".
- [Framework specification v1.0](https://behaveswellframework.com/specification), section
  "The Six Responsibilities", lists Truth, Identity, Operational Trust, Stewardship, Continuity,
  Concierge, without Foundation.
- [HTBW public Framework page](https://www.homesthatbehavewell.com/framework) says "Six connected
  responsibilities".
- At that time the accepted repository North Star required seven, in Foundation → Stewardship →
  Identity → Truth → Continuity → Operational Trust → Concierge order.

**Resolution (DL-153):** the public six-stage set and order are correct; Foundation is Layer 0, not a
stage. The remaining public stage-definition wording (Identity 02.01, Operational Trust 03.02/03.03,
Continuity 05.01) is tracked at
[Core #215](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/215).
No public website was edited from this repository.
