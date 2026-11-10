# BehavesWell Extended Intelligence product identity and compatibility boundary

> **Accepted authority restatement** (Owner decision recorded in HTBW **DL-153**, 2026-11-10), plus
> repository compatibility and documentation dispositions for this repository. Implementation issue:
> [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6).
> Governing record: [DL-153 ADR](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-behaveswell-framework-foundation-core-edition-and-context-identity.md)
> ([Core issue #214](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/214)).
> This document does not restate or re-decide the Framework/Core architecture; DL-153 governs it.

## Decision restated

**BehavesWell Extended Intelligence is the current canonical name of the product formerly developed
under the working name Home Steward.** It is a **rename of one product identity**. It is not a second
product, a fork, or a new product boundary. The product boundary accepted as **DL-131**
([ADR](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-home-steward-product-boundary.md))
continues unchanged under the new name.

| Name | Status |
|---|---|
| **BehavesWell Extended Intelligence** | Current canonical product name |
| **BehavesWell © Extended Intelligence** | Formal branded notation only (§ Copyright notation) |
| **Home Steward** | Former working/public name. Retained in historical text and in stable technical identifiers |

## Product definition

BehavesWell Extended Intelligence is an **independent, private and local-first intelligence product
for governed reasoning across explicitly authorized sources**. Its scope is DL-131's: it may supply
knowledge, synthesis, explanation, candidate relationships and proposals to responsible governed
capabilities. It never supplies authority.

**"Extended" describes the breadth of explicitly authorized reasoning context. It does not describe an
extension of operational authority.** It never means:

- extended authority, unrestricted source access, or blanket household or building access;
- permission to bypass Operational Trust, or automatic provider discovery;
- autonomous external-system action, or ownership of connected data;
- cloud-first processing;
- permission to control BehavesWell Core or Home Assistant;
- a new Framework stage or a new Core layer.

No source connection expands authority beyond what is explicitly granted for that source and action.
**The presence of information does not grant authority to act upon it.**

## What it is not

| It is not | Why (governing authority) |
|---|---|
| A BehavesWell Framework stage | The Framework has six stages: Truth, Identity, Operational Trust, Stewardship, Continuity, Concierge (DL-153) |
| Layer 0 Foundation | Foundation is the implementation-platform substrate of BehavesWell Core (DL-153) |
| BehavesWell Core, a Core component, or a Core Edition | BehavesWell Core is the separate product; its current and only edition is BehavesWell Core, Home Assistant Edition (DL-153). The product is not bundled into Core, is not required for Core to function, and is not a "Layer 7" |
| **Stewardship** | Stewardship is Framework stage 4. This product is not an implementation, owner, service, or "AI version" of Stewardship, and it may reason about Stewardship information only through authorized, governed interfaces. The rename deliberately removes the *Home Steward* / *Stewardship* collision |
| **Concierge** | Concierge (stage 6) keeps governed interaction and orchestration. This product owns no conversation authority, interaction-space, Person or Room resolution, action policy, orchestration, or execution |
| **Home Intelligence** | Home Intelligence is DL-86's optional deployment/hosting boundary for intelligence about the Home. This product may *optionally* be hosted within it (DL-131), and may serve as a provider or source for a capability only where separately authorized and configured. It does not become Home Intelligence because Core uses it, and it is **not** a default Home Intelligence provider |
| **General Reasoning** | General Reasoning is DL-93's configured capability. Resolution stays Person → Integration-default → unavailable, with **no Room step** and no runtime discovery. This product is never inserted into the General Reasoning fallback chain, and its gate is independent of Allow General Questions. This rename invents no provider-selection behavior |

**BehavesWell Core functions without BehavesWell Extended Intelligence.** Any integration between the
two products is explicit, bounded, authorized, separately configured, contract-based, explainable, and
revocable ([proposed integration contract](htbw-integration-contract.md)). The product may have
independent uses outside a BehavesWell Core installation only where separately governed.

**Homes That Behave Well** is the residential research, education, and evidence ecosystem (DL-153).
This product is not renamed to a residential name and is not architecturally limited to the residential
context.

## Local and private processing

Unchanged ([locality](locality-and-private-operation.md)): local means household- or
environment-controlled processing inside the governed private network boundary. It may use:

- a separate private-AI or RAG appliance;
- local inference, indexing, or document processing;
- explicitly authorized local connections.

It does not require the Home Assistant host. Processing stays inside the boundary unless an external
relationship is explicitly configured and authorized. **Nothing here makes the architecture
cloud-first.**

## Authorized sources — maturity classification

**No source is currently implemented. This repository contains no runtime.** Every connection must be
explicitly authorized, scoped to a source or resource, revocable, understandable, and governed
([source authorization](source-authorization.md)).

| Potential source | Classification | Basis |
|---|---|---|
| BehavesWell Core information (Home model, governed context) | **Accepted architecture**, not implemented | DL-131 (consumes Core/Home Intelligence context through governed boundaries); transport [proposed](htbw-integration-contract.md) |
| Home Assistant information | **Accepted architecture via BehavesWell Core, Home Assistant Edition**, not implemented; any direct relationship is **planned/proposed** | DL-131; [HA interface research](../research/home-assistant-ai-integration-surface.md) |
| Household documents (manuals, warranties, insurance, maintenance, Asset documents) | **Accepted architecture**, not implemented | DL-131, DL-81 |
| Financial and banking records, as authorized knowledge | **Accepted architecture**, not implemented; transaction authority explicitly excluded | DL-131 |
| Building or other environmental documents outside a household | **Illustrative possibility** | Not governed for any non-residential context |
| NAS or connected document sources | **Planned capability** (proposed requirement) | [Governed source connections](governed-source-connections.md) |
| Email | **Planned capability**, non-committal directional family | DL-131 ("household correspondence/email intelligence") |
| Calendar | **Planned capability**, non-committal directional family | DL-131 ("calendar-context reasoning") |
| Historical records and history | **Scenario or vision**; consumed by reference to the owning Core responsibility, never copied as a second history | [Knowledge architecture](knowledge-architecture.md) |
| Research material; public or external knowledge | **Planned capability** (proposed "permitted external research"), separately authorized outbound | [Extension model](home-steward-extension-model.md), [locality](locality-and-private-operation.md) |
| Other local services (for example media or MCP services) | **Illustrative possibility** | [Locality](locality-and-private-operation.md) |

## Stable technical identifiers retained for compatibility

The public identity changes now. **Technical identifiers do not.** No migration is authorized, and no
parallel identifier is created.

| Identifier | Kind | Disposition |
|---|---|---|
| Repository `Homes-That-Behave-Well-LLC/home_steward`, its URLs and the local folder `home_steward` | Repository identity | Retained. A repository rename is not authorized by #6 |
| `docs/architecture/home-steward-extension-model.md`, `docs/assets/home-steward-hero.png` | Compatibility-sensitive filenames | Retained |
| `docs/scenarios/home-steward-operations-and-self-stewardship/` and every scenario filename containing `home-steward` | Compatibility-sensitive paths | Retained; these are linked from the register, the scenario map, and external references |
| The DL-93 Person capability gate **Allow Home Steward** | BehavesWell Core-owned setting name | Retained. It is Core's accepted DL-93 vocabulary; any rename belongs to Core governance |
| Historical issue titles and commits (#1–#5, prior commits) | Historical record | Retained |

There is no package, module, namespace, service, API, storage namespace, environment variable,
container, database, or persisted key in this repository today. Future technical identifiers require
their own governed naming decision. **Candidate for later migration, not authorized:** the repository
name and the `home-steward` path segments, only after a separate compatibility plan that preserves
external links.

## How existing text is read

- **Current canonical documents** in this repository use **BehavesWell Extended Intelligence**.
- **Scenarios** (Vision and developed) and **dated research notes** were written under the former name.
  There, *Home Steward* means BehavesWell Extended Intelligence. They are not rewritten; a transition
  note in the [scenario map](../scenarios/README.md) and the [research catalog](../research/README.md)
  records this. The section names *"Possible Home Steward extension"* and *"Home Steward synthesis"* in
  the scenario formats are retained for consistency across the corpus.
- **HTBW**, in these documents, follows the Core glossary reading (DL-153): it names BehavesWell Core
  (Home Assistant Edition) where it means software, and Homes That Behave Well where it means the
  residential context.

## Copyright notation

- Use **BehavesWell Extended Intelligence** in normal, searchable product and technical surfaces.
- Reserve **BehavesWell © Extended Intelligence** for visual lockups, About surfaces, the first formal
  reference in selected current documentation, brand-system documentation, and selected website copy.
- **©** never appears in any repository, package, module, import path, filename, path, storage
  namespace, API, service, event, environment variable, configuration key, persisted identifier, URL,
  or documentation anchor.
- The product notation is not a legal notice. The standard notice is **© 2026 Homes That Behave Well
  LLC**.
- No trademark registration or legal status is implied. The ™ shown on the historical hero artwork
  likewise establishes nothing.

## Terms

This repository has no separate glossary. The canonical glossary is BehavesWell Core's
([glossary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/models/glossary.md));
the terms below are restated for this product and add nothing to it.

| Term | Meaning here |
|---|---|
| **BehavesWell Extended Intelligence** | The independent, private, local-first product for governed reasoning across explicitly authorized sources (DL-131 boundary; DL-153 name) |
| **Home Steward** | Former working/public name of BehavesWell Extended Intelligence. Historical, and retained in technical identifiers. Not a separate product |
| **BehavesWell Core** | The separate product implementing the six-stage Framework over Layer 0 Foundation; current edition BehavesWell Core, Home Assistant Edition (DL-153) |
| **Stewardship** | Framework stage 4 — what matters and must be cared for. Not this product |
| **Home Intelligence** | DL-86's optional deployment/hosting boundary capability for intelligence about the Home. Not this product's name |
| **General Reasoning** | DL-93's configured reasoning capability with its own provider resolution and gate. Not identical to this product |
| **Provider** | A configured supplier of a capability. Configuring one is a separate, explicit authorization; provider selection is never permission (DL-93) |
| **Authorized source** | A specific source or resource the household has explicitly admitted, scoped by person, purpose, and operation, and revocable |
| **Local / private processing** | Processing inside the household- or environment-controlled, governed private network boundary; not necessarily on the Home Assistant host |
| **Extended reasoning context** | The breadth of explicitly authorized sources available to reasoning. Never authority |
| **Operational authority** | Permission to act, disclose, or change state. It is evaluated by Operational Trust in BehavesWell Core and is never acquired through source access |

## Visual identity disposition

No final visual asset is created or approved here. The product mark is separate follow-on design work.

The product mark must **not** be:

- the Stewardship leaf, a BehavesWell Interlock Framework block, the Homes That Behave Well house mark,
  or the BehavesWell Core mark;
- a robot, a chatbot bubble, a brain, or generic AI sparkle imagery;
- any symbol implying unrestricted intelligence or authority.

It needs an **independent, environment-neutral** mark that shares BehavesWell visual discipline
without appearing to be a Framework stage, a Core component, a residential-only product, or
Stewardship.

| Existing asset | Classification | Disposition |
|---|---|---|
| `docs/assets/home-steward-hero.png` (shows "Home Steward™ … Built on Homes That Behave Well", residential imagery) | **Historical** (former name and residential framing) | Retained, not deleted, and not rebranded. Removed from the README hero position; linked from the [register](../governance/document-register.md) as historical artwork |
