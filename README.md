# BehavesWell Extended Intelligence

> **Status: architecture and research baseline - AWAITING OWNER ACCEPTANCE REVIEW.**
> Accepted HTBW boundaries are inherited; new product-specific requirements are proposals.
> [Authority order](docs/governance/authority-order.md) |
> [Document register](docs/governance/document-register.md) |
> [Open questions](docs/governance/open-questions.md).

**BehavesWell Extended Intelligence, formerly developed under the working name Home Steward, is an
independent private and local-first intelligence product for governed reasoning across explicitly
authorized sources.**

It is its own product. It is not part of the BehavesWell Framework or of BehavesWell Core:

- It is not a Framework stage, not Stewardship, and not BehavesWell Core or one of its Editions.
- "Extended" means a wider set of sources the household has explicitly authorized it to reason over.
  It never means wider authority.
- Connecting a source gives it no operational authority. Knowledge does not create authority.
- Some technical identifiers, such as this repository's name `home_steward` and `home-steward` file
  paths, keep the former name so existing links and references continue to work.

The rename is governed by
[DL-153](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-behaveswell-framework-foundation-core-edition-and-context-identity.md)
([Core #214](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/214)) and
implemented under [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6). It is one
product renamed, not a second product. Details:
[product identity and compatibility boundary](docs/architecture/product-identity-and-compatibility-boundary.md).

BehavesWell Core gives the Home a governed model of itself and the household. BehavesWell Extended
Intelligence lets the household explore, extend, retrieve, synthesize, and reason over that governed
knowledge using household-authorized private information and, where explicitly permitted, external
knowledge.

It is not the Home's source of Truth and does not determine what actions are permitted.

It is designed for local, household-controlled operation above a replaceable private-AI platform. The
platform may run on a separate appliance inside the governed Home network boundary. It does not
require BehavesWell Core to build its own inference hardware, model runtime, RAG engine, vector
database, or generic agent platform.

> *Naming in this repository.* "HTBW" below refers to BehavesWell Core, Home Assistant Edition (the
> software) or to Homes That Behave Well (the residential context), as defined in the
> [Core glossary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/models/glossary.md).
> Scenarios and dated research notes written before the rename still say *Home Steward*; read it as
> BehavesWell Extended Intelligence.

## Current status

- Architecture, scenarios, requirements and public-source research are active.
- No production runtime or executable implementation.
- No selected platform, provider, model or required hardware.
- No Home Assistant or MCP integration implemented.
- No installation, model download, connector activation or qualification testing.
- No vendor relationship, partnership, purchase, endorsement or upstream acceptance.
- Candidates are evaluated against architecture; architecture is not reshaped to fit candidates.
- Five bootstrap and research issues ([#1-#5](#status-and-roadmap)) plus the product-identity
  transition ([#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6)).

The public Framework and the repository are now reconciled by DL-153: the BehavesWell Framework has
six stages (Truth, Identity, Operational Trust, Stewardship, Continuity, Concierge), and Foundation is
Layer 0 of a BehavesWell Core implementation, not a seventh stage. Public stage wording remains at
[Core #215](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/215).
See [Framework relationship](docs/architecture/behaves-well-framework-relationship.md).

<a id="why-home-steward-exists"></a>
## Why BehavesWell Extended Intelligence exists

A household should be able to understand its Home and its authorized documents without placing its
knowledge, relationships or future options under one AI vendor's control. BehavesWell Extended Intelligence adds
knowledge exploration, not a new authority over the Home or the people in it.

## Scenario-First Development

BehavesWell Extended Intelligence is developed scenario first: preserve household questions, experiences and possibilities
before choosing their solution.

**SCENARIO -> RECURRING REQUIREMENT -> ARCHITECTURE -> GOVERNED IMPLEMENTATION -> ACCEPTANCE -> LIVED EVIDENCE**

The [scenario-family map](docs/scenarios/README.md) organizes developed scenarios and short-form Vision
ideas using explicit in-file maturity. Inclusion is **not a roadmap, ownership decision or acceptance**.
A scenario may be satisfied by HTBW, Home Assistant, BehavesWell Extended Intelligence, a private-AI platform, a specialist,
a professional, deterministic automation, another governed capability, or no technology at all.
Architecture and implementation remain separately governed; the catalog does not authorize either.

<a id="relationship-to-the-behaves-well-framework"></a>
## Relationship to the BehavesWell Framework

The [BehavesWell Framework](https://behaveswellframework.com/) — six stages — remains the common
governance architecture, not a competing AI framework. **BehavesWell Core** applies it over a Layer 0
Foundation; its current edition is **BehavesWell Core, Home Assistant Edition**.
[Homes That Behave Well](https://www.homesthatbehavewell.com/) is the residential research and evidence
ecosystem. The [BehavesWell Core repository](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well)
governs the responsibility boundaries consumed here.

BehavesWell Extended Intelligence creates no Framework stage and no Core layer, and it does not
implement the Framework. Human Trust remains an earned outcome; Behavioral Governance and
explainability remain cross-cutting.
[Responsibility mapping](docs/architecture/behaves-well-framework-relationship.md).

## Relationship to HTBW

HTBW supplies the governed Home model, context and decisions. BehavesWell Extended Intelligence consumes it by reference
through [governed interfaces](docs/architecture/htbw-integration-contract.md), behind native
[Home Assistant](https://www.home-assistant.io/) Assist and HTBW Concierge. It does not create a
competing household chatbot or insert itself into a General Reasoning fallback.

The accepted [DL-131 product boundary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-home-steward-product-boundary.md)
(recorded under the former name), DL-81 knowledge pipeline, DL-82 provenance and DL-93 independent
Person capability gates (including the Core-owned **Allow Home Steward** gate name) remain controlling.
Home Intelligence (DL-86) is an optional hosting boundary capability, not another name for this
product and not its default provider relationship. General Reasoning (DL-93) is a separate configured
capability; it never falls back to this product.

## What HTBW already provides

Governed capabilities and relationships include Asset identity and Asset Type, descriptions for
different audiences, Room and location relationships, ownership, document/manual/policy associations,
Stewardship obligations and schedules, Truth, Identity, Continuity, Operational Trust, deterministic
Home behavior and explanation of HTBW decisions.

These are accepted architectural responsibilities, **not a claim that every capability is already
implemented**. The first BehavesWell Core (then presented as HTBW Core) Foundation slice is
implemented and accepted at
[#201](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/201).
None of these responsibilities must become dependent on BehavesWell Extended Intelligence.

<a id="what-home-steward-adds"></a>
## What BehavesWell Extended Intelligence adds

Authorized unstructured-document retrieval, question answering, RAG-or-successor retrieval,
synthesis, comparison, summarization, explanation, permitted external research, conversational
exploration, pattern identification and candidate relationship discovery.

BehavesWell Extended Intelligence may also help the household reason across authorized resource consumption, utility cost, rates, weather, occupancy and lived outcomes to understand where economizing is worthwhile without treating lower consumption as a better outcome by definition.

[Extension model](docs/architecture/home-steward-extension-model.md):
**HTBW native capability**, **BehavesWell Extended Intelligence extended capability**, **BehavesWell Extended Intelligence proposed action**.

HTBW can explain "Why didn't the Dining Room shades close last night?" BehavesWell Extended Intelligence can extend
the inquiry: "Has that been happening more often?", "When did it start?", "What changed around then?",
"Did the fix actually work?" and "What evidence are we missing?" Native historical reconstruction
remains HTBW's; [cross-source investigation](docs/architecture/knowledge-architecture.md#htbw-explainability-and-home-steward-investigation)
adds evidence-bounded interpretation, not guessed causes or permission to act.

### Possibility and Improvement Discovery

HTBW governs the Home the household has. BehavesWell Extended Intelligence may help the household understand the Home
that has become possible by comparing authoritative platform changes with authorized configuration,
history, requests, friction and deferred ideas. It may recommend; implementation requires separate
governed authorization. [Architecture and maturity model](docs/architecture/possibility-and-improvement-discovery.md).
It may also [help steward HTBW itself](docs/architecture/htbw-architecture-stewardship.md), identifying
where native platform evolution warrants governed reconsideration, simplification, migration or
retirement of custom mechanisms without surrendering HTBW governance.

### Entertainment and Media Discovery

BehavesWell Extended Intelligence may help identify media from incomplete descriptions, explore separately authorized
private and streaming libraries, and clarify titles, artists and availability before any governed
Home action. Discovery need not imply playback; the execution mechanism remains an open architectural
question. [Scenario family](docs/scenarios/entertainment-and-media/README.md).

### Aging in Place and Care Awareness

With explicit person-level authorization, BehavesWell Extended Intelligence may help understand changes in wearable,
activity, Home and care-related evidence over time, prepare observation summaries and support
caregiver conversations. These scenarios are not medical diagnosis, clinical monitoring or emergency
decision-making; implementation remains open.
[Scenario family](docs/scenarios/aging-in-place/README.md).

### Ambient household intelligence

Many BehavesWell Extended Intelligence scenarios begin as household questions. The longer-term vision also explores
whether separately authorized local intelligence can recognize meaningful change without requiring
the household to know which question to ask first. **Noticing is not authority.** Observation does
not automatically become Truth, diagnosis, disclosure, retained memory, recommendation or action.

The [scenario corpus](docs/scenarios/README.md#ambient-and-household-intelligence-increment) also
explores visual household evidence, multimodal context, long-running inquiry, household knowledge
review, evidence challenge, Person-versus-household boundaries, ephemeral evidence, controlled
correction, local personalization, offline intelligence, multiple interaction surfaces and
stewardship of BehavesWell Extended Intelligence itself. These remain Vision questions, not implemented mechanisms.

### Reference Home discovery

The [Reference Home walkthrough](docs/scenarios/reference-home-walkthrough.md) uses household spaces,
visits, care and outages as scenario-discovery perspectives. It links existing coverage and new
Vision questions about arrival, Room capabilities, situated references, commissioning, dependencies,
temporary stewardship and lived evidence. It is navigation, not an inventory, BOM, runtime design
or a claim that BehavesWell Extended Intelligence can access the described systems.

<a id="what-home-steward-does-not-own"></a>
## What BehavesWell Extended Intelligence does not own

Foundation; Stewardship; Identity; Truth; Continuity; Operational Trust; Concierge; authoritative
Home state; household intent; consent; action authority; the Decision Trace; Home Assistant execution;
original Asset documents; or a competing household catalog.

Foundation holds consent records; Identity owns their lifecycle; Operational Trust applies consent
policy. Adding AI does not move those owners. [Boundary](docs/architecture/htbw-boundary.md).

## Definition of local

Local means processing, storage, derived knowledge, inference, retrieval, embeddings, RAG, memory and
approved service relationships remain inside the **household-controlled, governed Home network
boundary**. A separate private-AI appliance qualifies geographically; its governance still must pass.

Local does not require the HA host, HAOS, HTBW integration, process, container, computer or VLAN.
Local does not mean unrestricted: each service, namespace, source, account, API, connector and tool
relationship is explicitly admitted and scoped.

External source retrieval is a separately authorized network operation, not permission to send
household context to public search or remote inference. [Locality contract](docs/architecture/locality-and-private-operation.md).

## Governed source relationships

Each source is independently governed across connection, ingestion, parsing/OCR, extraction/indexing,
embedding, retention, retrieval, disclosure, person/application scope, reasoning, proposal and action.
NAS access does not grant access to every share. A person's mailbox does not become a household inbox.

[Source connections](docs/architecture/governed-source-connections.md) |
[Authorization requirements](docs/architecture/source-authorization.md).

## Knowledge versus authority

Knowledge is not authority. Access is not disclosure. Reasoning is not consent.
Recommendation is not authorization. An AI result is not permission to act.
Credentials, tools, a previous similar action or an available MCP endpoint do not grant permission.

Every proposed action returns through HTBW and Operational Trust before any authorized executor acts.
[Reasoning boundary](docs/architecture/reasoning-and-authority-boundary.md).

## Private-AI platform independence

The platform may supply commodity inference, models, parsing/OCR, embeddings, vector storage, RAG,
controlled memory, agent scheduling, MCP/APIs, administration, health, updates and backup/recovery.
BehavesWell Extended Intelligence supplies governed household intelligence above it.

Replaceability includes sources, configuration, derived-data lineage, export and reconstruction,
not merely changing the model name. [Host contract](docs/architecture/private-ai-host-platform-contract.md).

## Painting: "Tell me about this painting"

HTBW resolves the Asset and its governed descriptions/relationships. BehavesWell Extended Intelligence may retrieve
authorized provenance, purchase, conservation, appraisal and insurance evidence; public artist
research remains external evidence. A possible trip association stays a candidate until attributable,
authorized confirmation and governed promotion.

[Full ten-turn painting scenario](docs/scenarios/asset-intelligence/tell-me-about-this-painting.md).

## Appliance and manual

HTBW resolves the exact Asset/model and associated manual. BehavesWell Extended Intelligence can interpret authorized
instructions and service records, while Truth retains current state and Stewardship retains care.
Scheduling or contacting anyone needs separate authority.
[Appliance scenario](docs/scenarios/asset-intelligence/how-do-i-use-this-appliance.md).

## Maintenance and Stewardship

HTBW determines why an obligation is due from configured care and eligible evidence. BehavesWell Extended Intelligence
may explain manufacturer/service guidance or gaps, not silently rewrite a care cycle or mark work done.
[Maintenance scenario](docs/scenarios/asset-intelligence/why-is-this-maintenance-due.md).

## Insurance and a living inventory

A rider is a dated snapshot. Governed Asset relationships plus authorized document interpretation
can support a living household-controlled inventory and proposed claim-support package.
BehavesWell Extended Intelligence cannot bind coverage, change a policy or contact an insurer without authorization.
[Insurance scenario](docs/scenarios/asset-intelligence/is-this-asset-properly-insured.md).

## Relationship Discovery

An inferred trip, renovation or family association is not a durable relationship or Truth.
Evidence, candidate status, attribution and household confirmation remain distinct.
The final promotion/lifecycle mechanism is open.
[Discovery](docs/architecture/relationship-discovery.md) |
[Derived knowledge lifecycle](docs/architecture/derived-knowledge-lifecycle.md).

## Platform research

The [research catalog](docs/research/README.md) separates official product claims, technical
documentation, independent evidence, inference and unknowns. No candidate is qualified by this
baseline. Hardware, generic APIs and "local AI" marketing do not prove governed source access.

[Qualification gates](docs/platforms/qualification-gates.md) |
[Compatibility matrix](docs/platforms/compatibility-matrix.md).

## Ghost Core research status

**RESEARCH INCOMPLETE; not selected.** Public FAQ claims include a local OpenAI Responses
API-compatible endpoint and external coding-agent use without per-token local inference fees.
These are attributed vendor claims, not an executed compatibility benchmark.

The public privacy policy also describes online managed services and memories/copies that can survive
source removal. Those disclosures require investigation; they must not be hidden behind "on-device".
The Owner initiated a technical inquiry; no private correspondence is published.
[Detailed Ghost profile](docs/research/ghost-core.md).

## Repository map

| Area | Start here |
|---|---|
| Architecture and boundaries | [North Star](docs/architecture/north-star.md) |
| Governance, decisions and unresolved questions | [Authority](docs/governance/authority-order.md) |
| Platform requirements and proposed evaluation | [Requirements](docs/platforms/host-platform-requirements.md) |
| Dated public-source candidate research | [Catalog](docs/research/README.md) |
| Scenario-first household questions and boundary tests | [Scenario-family map](docs/scenarios/README.md) |
| Complete file/status inventory | [Document register](docs/governance/document-register.md) |

## Current non-goals

No executable runtime, integration scaffolding, MCP implementation, inference/model/vector/RAG/agent
installation, platform selection, procurement, endorsement, source credentials, private household
inventory, email publication, or production/HA-DEV deployment.

No fine-grained authorization taxonomy, universal retention value or deletion engine is silently
settled by creating documents. [Scope and non-goals](docs/architecture/scope-and-non-goals.md).

## Status and roadmap

Milestone: **BehavesWell Extended Intelligence: Architecture and Platform Qualification** (no due date).

| Issue | Work | Status |
|---|---|---|
| [#1](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/1) | Bootstrap architecture/research baseline | AWAITING OWNER ACCEPTANCE REVIEW |
| [#2](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2) | Common vendor-neutral qualification standard | OPEN, RESEARCH REQUIRED |
| [#3](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/3) | Ghost Core qualification review | RESEARCH INCOMPLETE |
| [#4](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/4) | Comparative appliance review | OPEN, RESEARCH REQUIRED |
| [#5](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5) | Reference software / DIY control | OPEN, RESEARCH REQUIRED |
| [#6](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/6) | Product identity: Home Steward → BehavesWell Extended Intelligence (DL-153) | IMPLEMENTED IN DOCUMENTATION; OWNER REVIEW |

#1 has no issue prerequisite. #2 depends on #1's baseline. #3-#5 may gather public evidence before #2
closes; final qualification/comparison cannot precede #2 Owner acceptance. #5 supplies the control
baseline for #3/#4. No evaluation or runtime testing started in this bootstrap. #6 records the DL-153
product-identity transition; it changes names in documentation only.

Candidate outcome vocabulary: **QUALIFIED FOR REFERENCE HOME VALIDATION**, **QUALIFIED WITH CONDITIONS**,
**RESEARCH INCOMPLETE**, **NOT QUALIFIED**, **DEFERRED, MARKET NOT MATURE**.

## Reference Home relationship

Reference Home observations are a separate, explicitly authorized evidence step, not implied by
documentation or vendor demonstrations. Later tests must use approved scope, safe/synthetic data,
rollback, locality controls and Owner eyes-and-ears acceptance. No live household testing occurred here.

## Contributing and licensing

Read [CONTRIBUTING](CONTRIBUTING.md), [security policy](SECURITY.md) and
[conduct expectations](CODE_OF_CONDUCT.md). Cite sources without copying licensed source material or
private correspondence. Public visibility is not a license grant.

Organization repositories have mixed licensing conventions. **All rights remain reserved until
explicitly licensed.** No permissive or open-source license is added. Licensing is an
[open governance question](docs/governance/open-questions.md#licensing).

## Links

- [Homes That Behave Well](https://www.homesthatbehavewell.com/)
- [BehavesWell Framework](https://behaveswellframework.com/)
- [BehavesWell Core repository](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well)
- [Home Assistant](https://www.home-assistant.io/)
- [Official HA developer documentation](https://contributors.home-assistant.io/core/)

**No platform has been selected. No executable BehavesWell Extended Intelligence implementation exists in this repository.**

## Names and notices

*BehavesWell © Extended Intelligence* is the formal branded notation for the product named
**BehavesWell Extended Intelligence**. It is not a legal notice, and no trademark or other legal status
is asserted. The earlier hero artwork, which shows the former name, is retained as
[historical artwork](docs/assets/home-steward-hero.png) and is not the product's visual identity. A new,
environment-neutral product mark is separate follow-on design work.

© 2026 Homes That Behave Well LLC
