# HTBW boundary

> Accepted HTBW boundary restatement; new interface details are proposed and await Owner review.
> [DL-131](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-home-steward-product-boundary.md).

| Owner | What BehavesWell Extended Intelligence consumes | What does not move |
|---|---|---|
| Foundation | Asset/Person/Room identity, vocabulary, source/document/capability relationships | Descriptive model, durable relationships and original document management |
| Stewardship | Governed care obligations, schedules, requirements and disposition | Creation, change, satisfaction and authority of obligations |
| Identity | Effective Person resolution and eligible context | Identity assertions, consent lifecycle and person entitlement |
| Truth | Applicable current/historical Facts and evidence boundaries | Authoritative Home state and Fact history |
| Continuity | Applicable session/context/prior interaction state | Session/experience continuity and governed remembered values |
| Operational Trust | Scope and decision for this request/context | Access/disclosure/privacy/confirmation/autonomy/permission policy |
| Concierge | Orchestrated request, output channel and proposed next step | Household workflow, decision composition, execution routing and Trace composition |

Foundation holds consent records; Identity owns their lifecycle; Operational Trust owns consent
policy. Knowledge retrieval must not conflate these.

Assist -> Concierge/responsible capability -> BehavesWell Extended Intelligence -> result -> responsible capability ->
HTBW governance -> appropriate native response or authorized execution.

Ordinary native document display, asset identity and deterministic Home control do not require AI.
Do not duplicate a native HA Person/Area/entity/device or original document store.
Neither authorization tokens nor transport success prove a physical outcome.

Home Intelligence (DL-86) is an optional hosting "where". BehavesWell Extended Intelligence (DL-131, formerly Home Steward) is a knowledge
product/domain "what". Household Knowledge Provider (DL-81) is a consumed pipeline, not a new
responsibility. General Reasoning (DL-93) remains independent and never silently substitutes.
