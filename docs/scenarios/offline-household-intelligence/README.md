# Offline Household Intelligence

Navigation and scenario-capture guidance only; not architecture, a roadmap or delivered functionality. Browse the [scenario-first map](../README.md).

## Purpose

Distinguish an eligible locally held answer from an external-source dependency, unavailable fresh evidence or a disclosure. Local means within the household-controlled network boundary, not necessarily one computer.

## Relationship to HTBW

Foundation describes structure, not current Truth; Stewardship owns household-declared significance, care, obligations and accepted Custody; Identity supplies Person/context, not authentication or authorization; Truth owns current/historical Facts; Continuity retains accepted preference/session/experience responsibilities; Operational Trust determines permission/disclosure for this request/context; Concierge retains governed orchestration and Trace, not centralized ownership or acceptance. Native Explainability already includes historical/time/cross-Room retrieval. Home Assistant/devices retain execution.

See the accepted-owner [HTBW boundary](../../architecture/htbw-boundary.md), [source authorization](../../architecture/source-authorization.md) and [derived lifecycle](../../architecture/derived-knowledge-lifecycle.md).

## Boundaries

NOTICE != DIAGNOSE; NOTICE != DISCLOSE; NOTICE != RETAIN; NOTICE != RECOMMEND; NOTICE != ACT. Noticing is not authority or automatic Truth, household significance, notification or action.

Potential evidence is not admitted access. Person/source/purpose/namespace/audience gates remain independent; one Person's grant is not everyone's access and cross-person grants do not merge. The most restrictive applicable source constraints remain binding. Summaries can disclose their sources; conclusions are not automatically safe to share. USE != INGEST != DERIVE != RETAIN. Derived information remains source-bound through correction, retention, expiry, deletion and revocation within the household-controlled network boundary. Household-configured ordinary retention may be zero/disabled; no numeric minimum or maximum is imposed. Confirmation alone does not grant retention, disclosure, policy or action authority. No shadow history or silent cloud/source fallback.

Observation, source report, comparison and inference are not automatic Truth. Correlation is not causation; unknown is valid. Issued command != observed physical result. People and Pets are not Assets; Pet/device location does not flow through human Identity. No diagnosis, prognosis, treatment or medical causation follows from changed observations. No medical, life-safety or emergency path depends on an LLM; native/deterministic/manual safety remains independent.

All future source eligibility, meaningful-change review, retention, correction, disclosure, notification and action questions remain OPEN ARCHITECTURAL QUESTIONS. No runtime, scheduler, camera pipeline, learning system, hook, consent engine, platform qualification or acceptance mechanism is designed here.

## Primary scenarios

Primary files: **0 developed + 6 Vision = 6**. Existing coverage and aliases do not add primary files or change target maturity.

- [What can Home Steward still answer without Internet connectivity?](what-can-home-steward-still-answer-without-internet-connectivity.md) — **VISION — NOT YET ARCHITECTED**. Without Internet access, some household questions may still use eligible sources inside the household-controlled network. The household wants that bounded capability distinguished from missing external information, rather than a private-AI label promising that every answer remains available or equally current.
- [Which household questions are fully local?](which-household-questions-are-fully-local.md) — **VISION — NOT YET ARCHITECTED**. A question can be local in subject yet depend on an outside provider for evidence. The household wants the complete declared source and operation boundary understood before answering, so a local screen or appliance does not hide egress, authorization dependencies or unavailable external freshness.
- [Which sources require external access?](which-sources-require-external-access.md) — **VISION — NOT YET ARCHITECTED**. Email, public research or vendor information can require external access even when fetched directly by a local appliance. The household wants those dependencies distinguished from authorized local documents, without a useful source being treated as permission to connect or disclose inquiry context.
- [Which external information has already been safely retained locally?](which-external-information-has-already-been-safely-retained-locally.md) — **VISION — NOT YET ARCHITECTED**. External information may have been legitimately retained locally for a limited purpose. The household wants its source date, expiry and revocation constraints preserved during an outage, rather than a local copy being treated as permanently reusable, current or independent of the original source's lifecycle.
- [Can Home Steward explain when an answer would require information to leave the Home?](can-home-steward-explain-when-an-answer-would-require-information-to-leave-the-home.md) — **VISION — NOT YET ARCHITECTED**. An answer may require a query or source request that reveals household information outside its boundary. The household wants that requirement explained before egress, because absence of raw documents in the request does not make the inquiry topic or derived context harmless to disclose.
- [Can the household choose a lower-confidence local-only answer?](can-the-household-choose-a-lower-confidence-local-only-answer.md) — **VISION — NOT YET ARCHITECTED**. A household may prefer a limited local answer to sending information outside. The useful outcome is explicit reduced evidence scope and unknowns, not a model manufacturing certainty, weakening authoritative Truth or calling an unsupported guess a lower-confidence factual answer.

## Requested-entry coverage

| Entry | Requested wording | Primary coverage | Disposition and rationale |
|---|---|---|---|
| offline-1 | What can Home Steward still answer without Internet connectivity? | [What can Home Steward still answer without Internet connectivity?](what-can-home-steward-still-answer-without-internet-connectivity.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-2 | Which household questions are fully local? | [Which household questions are fully local?](which-household-questions-are-fully-local.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-3 | Which sources require external access? | [Which sources require external access?](which-sources-require-external-access.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-4 | Which external information has already been safely retained locally? | [Which external information has already been safely retained locally?](which-external-information-has-already-been-safely-retained-locally.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-5 | Can Home Steward explain when an answer would require information to leave the Home? | [Can Home Steward explain when an answer would require information to leave the Home?](can-home-steward-explain-when-an-answer-would-require-information-to-leave-the-home.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-6 | Can the household choose a lower-confidence local-only answer? | [Can the household choose a lower-confidence local-only answer?](can-the-household-choose-a-lower-confidence-local-only-answer.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| offline-7 | What functionality degrades without Internet access? | [What functionality degrades without Internet access?](../resilience-and-recovery/what-stops-if-the-internet-goes-down.md) | EXISTING COVERAGE — Existing documented Internet-dependency review distinguishes optional enrichment, actual operation and unknown vendor behavior. |
| offline-8 | What should remain fully available during an ISP outage? | [What should remain fully available during an ISP outage?](../resilience-and-recovery/what-stops-if-the-internet-goes-down.md) | EXISTING COVERAGE — Same dependency review applies to an ISP outage; see also native independence, without promising every capability remains available. |

## Future questions

**OPEN ARCHITECTURAL QUESTION:** How could the household inspect this bounded experience, its evidence gaps and source lifecycle without assigning new authority or selecting a mechanism? Promotion requires [separate governed review](../README.md#promotion). Issue #1 remains OPEN; this increment awaits Owner acceptance and does not resolve the separate publication-alignment disposition.
