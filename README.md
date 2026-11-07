# Home Steward

> **Status: architecture and research baseline - AWAITING OWNER ACCEPTANCE REVIEW.**
> Accepted HTBW boundaries are inherited; new Home Steward-specific requirements are proposals.
> [Authority order](docs/governance/authority-order.md) |
> [Document register](docs/governance/document-register.md) |
> [Open questions](docs/governance/open-questions.md).

Home Steward is the private household intelligence capability for a Home That Behaves Well.

HTBW gives the Home a governed model of itself and the household. Home Steward allows the household
to explore, extend, retrieve, synthesize, and reason over that governed knowledge using
household-authorized private information and, where explicitly permitted, external knowledge.

Home Steward is not the Home's source of Truth and does not independently determine what actions
are permitted. Knowledge does not create authority.

Home Steward is designed for local, household-controlled operation above a replaceable private-AI
platform. The platform may run on a separate appliance inside the governed Home network boundary.
Home Steward does not require HTBW to build its own inference hardware, model runtime, RAG engine,
vector database, or generic agent platform.

## Current status

- Architecture, scenarios, requirements and public-source research are active.
- No production runtime or executable implementation.
- No selected platform, provider, model or required hardware.
- No Home Assistant or MCP integration implemented.
- No installation, model download, connector activation or qualification testing.
- No vendor relationship, partnership, purchase, endorsement or upstream acceptance.
- Candidates are evaluated against architecture; architecture is not reshaped to fit candidates.
- Exactly [five open issues](#status-and-roadmap) govern the bootstrap and future research.

**Scoped REMEDIATION REQUIRED:** the public Framework currently describes six responsibilities,
while accepted HTBW authority requires seven including Foundation. This repository preserves HTBW's
accepted boundaries but does not claim those publications are reconciled.
See [the precise discrepancy](docs/architecture/behaves-well-framework-relationship.md#publication-discrepancy).

## Why Home Steward exists

A household should be able to understand its Home and its authorized documents without placing its
knowledge, relationships or future options under one AI vendor's control. Home Steward adds
knowledge exploration, not a new authority over the Home or the people in it.

## Relationship to the Behaves Well Framework

The [Behaves Well Framework](https://behaveswellframework.com/) remains the common governance
architecture, not a competing AI framework. [Homes That Behave Well](https://www.homesthatbehavewell.com/)
is its residential application and evidence context. The
[accepted HTBW repository](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well)
governs the responsibility boundaries consumed here.

Home Steward creates no eighth responsibility. Human Trust remains an earned outcome; Behavioral
Governance and explainability remain cross-cutting.
[Responsibility mapping and public-alignment caveat](docs/architecture/behaves-well-framework-relationship.md).

## Relationship to HTBW

HTBW supplies the governed Home model, context and decisions. Home Steward consumes it by reference
through [governed interfaces](docs/architecture/htbw-integration-contract.md), behind native
[Home Assistant](https://www.home-assistant.io/) Assist and HTBW Concierge. It does not create a
competing household chatbot or insert itself into a General Reasoning fallback.

The accepted [DL-131 product boundary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-home-steward-product-boundary.md),
DL-81 knowledge pipeline, DL-82 provenance and DL-93 independent Person capability gates remain
controlling. Home Intelligence is an optional hosting boundary, not another name for Home Steward.

## What HTBW already provides

Governed capabilities and relationships include Asset identity and Asset Type, descriptions for
different audiences, Room and location relationships, ownership, document/manual/policy associations,
Stewardship obligations and schedules, Truth, Identity, Continuity, Operational Trust, deterministic
Home behavior and explanation of HTBW decisions.

These are accepted architectural responsibilities, **not a claim that every capability is already
implemented**. The first HTBW Core Foundation slice is implemented and accepted at
[#201](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/issues/201).
None of these responsibilities must become dependent on Home Steward.

## What Home Steward adds

Authorized unstructured-document retrieval, question answering, RAG-or-successor retrieval,
synthesis, comparison, summarization, explanation, permitted external research, conversational
exploration, pattern identification and candidate relationship discovery.

[Extension model](docs/architecture/home-steward-extension-model.md):
**HTBW native capability**, **Home Steward extended capability**, **Home Steward proposed action**.

HTBW can explain "Why didn't the Dining Room shades close last night?" Home Steward can extend
the inquiry: "Has that been happening more often?", "When did it start?", "What changed around then?",
"Did the fix actually work?" and "What evidence are we missing?" Native historical reconstruction
remains HTBW's; [cross-source investigation](docs/architecture/knowledge-architecture.md#htbw-explainability-and-home-steward-investigation)
adds evidence-bounded interpretation, not guessed causes or permission to act.

### Possibility and Improvement Discovery

HTBW governs the Home the household has. Home Steward may help the household understand the Home
that has become possible by comparing authoritative platform changes with authorized configuration,
history, requests, friction and deferred ideas. It may recommend; implementation requires separate
governed authorization. [Architecture and maturity model](docs/architecture/possibility-and-improvement-discovery.md).
It may also [help steward HTBW itself](docs/architecture/htbw-architecture-stewardship.md), identifying
where native platform evolution warrants governed reconsideration, simplification, migration or
retirement of custom mechanisms without surrendering HTBW governance.

### Entertainment and Media Discovery

Home Steward may help identify media from incomplete descriptions, explore separately authorized
private and streaming libraries, and clarify titles, artists and availability before any governed
Home action. Discovery need not imply playback; the execution mechanism remains an open architectural
question. [Scenario family](docs/governance/document-register.md#entertainment-and-media-discovery).

### Aging in Place and Care Awareness

With explicit person-level authorization, Home Steward may help understand changes in wearable,
activity, Home and care-related evidence over time, prepare observation summaries and support
caregiver conversations. These scenarios are not medical diagnosis, clinical monitoring or emergency
decision-making; implementation remains open.
[Scenario family](docs/governance/document-register.md#aging-in-place-and-care-awareness).

## What Home Steward does not own

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
Home Steward supplies governed household intelligence above it.

Replaceability includes sources, configuration, derived-data lineage, export and reconstruction,
not merely changing the model name. [Host contract](docs/architecture/private-ai-host-platform-contract.md).

## Painting: "Tell me about this painting"

HTBW resolves the Asset and its governed descriptions/relationships. Home Steward may retrieve
authorized provenance, purchase, conservation, appraisal and insurance evidence; public artist
research remains external evidence. A possible trip association stays a candidate until attributable,
authorized confirmation and governed promotion.

[Full ten-turn painting scenario](docs/scenarios/tell-me-about-this-painting.md).

## Appliance and manual

HTBW resolves the exact Asset/model and associated manual. Home Steward can interpret authorized
instructions and service records, while Truth retains current state and Stewardship retains care.
Scheduling or contacting anyone needs separate authority.
[Appliance scenario](docs/scenarios/how-do-i-use-this-appliance.md).

## Maintenance and Stewardship

HTBW determines why an obligation is due from configured care and eligible evidence. Home Steward
may explain manufacturer/service guidance or gaps, not silently rewrite a care cycle or mark work done.
[Maintenance scenario](docs/scenarios/why-is-this-maintenance-due.md).

## Insurance and a living inventory

A rider is a dated snapshot. Governed Asset relationships plus authorized document interpretation
can support a living household-controlled inventory and proposed claim-support package.
Home Steward cannot bind coverage, change a policy or contact an insurer without authorization.
[Insurance scenario](docs/scenarios/is-this-asset-properly-insured.md).

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
| Household boundary tests | [Scenario template](docs/scenarios/scenario-template.md) |
| Complete file/status inventory | [Document register](docs/governance/document-register.md) |

## Current non-goals

No executable runtime, integration scaffolding, MCP implementation, inference/model/vector/RAG/agent
installation, platform selection, procurement, endorsement, source credentials, private household
inventory, email publication, or production/HA-DEV deployment.

No fine-grained authorization taxonomy, universal retention value or deletion engine is silently
settled by creating documents. [Scope and non-goals](docs/architecture/scope-and-non-goals.md).

## Status and roadmap

Milestone: **Home Steward: Architecture and Platform Qualification** (no due date).

| Issue | Work | Status |
|---|---|---|
| [#1](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/1) | Bootstrap architecture/research baseline | AWAITING OWNER ACCEPTANCE REVIEW |
| [#2](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2) | Common vendor-neutral qualification standard | OPEN, RESEARCH REQUIRED |
| [#3](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/3) | Ghost Core qualification review | RESEARCH INCOMPLETE |
| [#4](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/4) | Comparative appliance review | OPEN, RESEARCH REQUIRED |
| [#5](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/5) | Reference software / DIY control | OPEN, RESEARCH REQUIRED |

#1 has no issue prerequisite. #2 depends on #1's baseline. #3-#5 may gather public evidence before #2
closes; final qualification/comparison cannot precede #2 Owner acceptance. #5 supplies the control
baseline for #3/#4. No evaluation or runtime testing started in this bootstrap.

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
- [Behaves Well Framework](https://behaveswellframework.com/)
- [HTBW public repository](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well)
- [Home Assistant](https://www.home-assistant.io/)
- [Official HA developer documentation](https://contributors.home-assistant.io/core/)

**No platform has been selected. No executable Home Steward implementation exists in this repository.**
