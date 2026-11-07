# Multimodal Household Knowledge

Navigation and scenario-capture guidance only; not architecture, a roadmap or delivered functionality. Browse the [scenario-first map](../README.md).

## Purpose

Explore independently authorized image, video, document, audio, Home state, Asset, environmental and historical context without treating their combination as agreement, certainty or permission to disclose.

## Relationship to HTBW

Foundation describes structure, not current Truth; Stewardship owns household-declared significance, care, obligations and accepted Custody; Identity supplies Person/context, not authentication or authorization; Truth owns current/historical Facts; Continuity retains accepted preference/session/experience responsibilities; Operational Trust determines permission/disclosure for this request/context; Concierge retains governed orchestration and Trace, not centralized ownership or acceptance. Native Explainability already includes historical/time/cross-Room retrieval. Home Assistant/devices retain execution.

See the accepted-owner [HTBW boundary](../../architecture/htbw-boundary.md), [source authorization](../../architecture/source-authorization.md) and [derived lifecycle](../../architecture/derived-knowledge-lifecycle.md).

## Boundaries

NOTICE != DIAGNOSE; NOTICE != DISCLOSE; NOTICE != RETAIN; NOTICE != RECOMMEND; NOTICE != ACT. Noticing is not authority or automatic Truth, household significance, notification or action.

Potential evidence is not admitted access. Person/source/purpose/namespace/audience gates remain independent; one Person's grant is not everyone's access and cross-person grants do not merge. The most restrictive applicable source constraints remain binding. Summaries can disclose their sources; conclusions are not automatically safe to share. USE != INGEST != DERIVE != RETAIN. Derived information remains source-bound through correction, retention, expiry, deletion and revocation within the household-controlled network boundary. Household-configured ordinary retention may be zero/disabled; no numeric minimum or maximum is imposed. Confirmation alone does not grant retention, disclosure, policy or action authority. No shadow history or silent cloud/source fallback.

Observation, source report, comparison and inference are not automatic Truth. Correlation is not causation; unknown is valid. Issued command != observed physical result. People and Pets are not Assets; Pet/device location does not flow through human Identity. No diagnosis, prognosis, treatment or medical causation follows from changed observations. No medical, life-safety or emergency path depends on an LLM; native/deterministic/manual safety remains independent.

All future source eligibility, meaningful-change review, retention, correction, disclosure, notification and action questions remain OPEN ARCHITECTURAL QUESTIONS. No runtime, scheduler, camera pipeline, learning system, hook, consent engine, platform qualification or acceptance mechanism is designed here.

LAST OBSERVED != automatic CURRENT LOCATION. Nonvisibility in a frame is not proof of physical absence or current location. Camera/image access is separately governed by purpose, eligible Rooms, private-space exclusions and eligible requester; identifying people is not necessary merely because they appear. Guests and service providers retain their own privacy boundaries. Incorrect Person/object guesses never become Identity assertions or access authority. Ephemeral analysis does not authorize a durable derived fact, another image/video copy or hidden person/location memory. Deletion/revocation of a source continues to constrain derived location knowledge.

Every relevant image scenario, including existing cross-linked coverage, inherits these unresolved questions:

- **OPEN ARCHITECTURAL QUESTION:** Which cameras or images, and which exact purpose, could be authorized?
- **OPEN ARCHITECTURAL QUESTION:** Which Rooms are eligible, and which private Rooms or spaces are excluded?
- **OPEN ARCHITECTURAL QUESTION:** Who is eligible to request and receive this observation?
- **OPEN ARCHITECTURAL QUESTION:** Is person identification necessary at all for this object/evidence question?
- **OPEN ARCHITECTURAL QUESTION:** What source, working-copy and derived retention is separately permitted, including zero/disabled retention?
- **OPEN ARCHITECTURAL QUESTION:** What happens to derived location knowledge when source evidence is deleted or revoked?
- **OPEN ARCHITECTURAL QUESTION:** How are guests and service providers appearing in frames protected?
- **OPEN ARCHITECTURAL QUESTION:** Could the evidence be used ephemerally without durable image/video or person memory?
- **OPEN ARCHITECTURAL QUESTION:** Could a separately permitted, scoped fact be retained without another copy of the image/video?
- **OPEN ARCHITECTURAL QUESTION:** What do framing, gaps, timestamps, uncertain identification and occlusion prevent the evidence from establishing?

UniFi Protect is only an example of a future separately governed local relationship, not a selected integration, supported connector or implemented pipeline.

## Primary scenarios

Primary files: **0 developed + 5 Vision = 5**. Existing coverage and aliases do not add primary files or change target maturity.

- [Match this appliance label to the correct manual.](match-this-appliance-label-to-the-correct-manual.md) — **VISION — NOT YET ARCHITECTED**. Similar appliances may use different manuals despite resembling each other. The household wants a readable label linked only as a candidate to independently eligible exact-model documentation, so visual extraction does not substitute generic instructions for Asset-specific safe care.
- [Compare this equipment sound with the description from the prior service visit.](compare-this-equipment-sound-with-the-description-from-the-prior-service-visit.md) — **VISION — NOT YET ARCHITECTED**. A new equipment sound may resemble a written description from an earlier service visit. The household wants a cautious comparison of independently eligible audio and records, with recording context and terminology limits, rather than an inferred fault or a diagnosis from resemblance.
- [Read this instrument or meter shown in the service photograph.](read-this-instrument-or-meter-shown-in-the-service-photograph.md) — **VISION — NOT YET ARCHITECTED**. A service photograph may contain a readable meter or instrument display. The household wants the apparent characters, units and capture time distinguished from the instrument's actual accuracy or current measurement, especially when glare or missing context makes a reading ambiguous.
- [Compare the visible reading with the invoice or service record.](compare-the-visible-reading-with-the-invoice-or-service-record.md) — **VISION — NOT YET ARCHITECTED**. A photographed reading may differ from an invoice or service record for legitimate reasons. The household wants dates, units and recording conventions compared before treating disagreement as fraud, error or equipment failure, because neither source automatically establishes the household Fact.
- [What evidence across images and documents supports this conclusion?](what-evidence-across-images-and-documents-supports-this-conclusion.md) — **VISION — NOT YET ARCHITECTED**. Several evidence types may support an interpretation without independently agreeing. The household wants the attributable contribution and missing context visible, so an appealing multimodal answer does not hide that one source supplied the assumption on which the others were read.

## Requested-entry coverage

| Entry | Requested wording | Primary coverage | Disposition and rationale |
|---|---|---|---|
| multimodal-1 | Match this appliance label to the correct manual. | [Match this appliance label to the correct manual.](match-this-appliance-label-to-the-correct-manual.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| multimodal-2 | Does this serial number match the Asset record? | [Does this serial number match the Asset record?](../visual-evidence-and-household-observation/does-this-serial-number-match-the-asset-record.md) | NEW PRIMARY ALIAS — Exact repeated serial-number/Asset-record question; one primary includes image-to-record comparison. |
| multimodal-3 | Does today's photo show the same visible feature documented last year? | [Does today's photo show the same visible feature documented last year?](../visual-evidence-and-household-observation/does-this-image-show-the-same-condition-feature.md) | NEW PRIMARY ALIAS — Same visible-feature comparison across dated image/document records; one primary explicitly includes today's photo and last year's description. |
| multimodal-4 | Compare this equipment sound with the description from the prior service visit. | [Compare this equipment sound with the description from the prior service visit.](compare-this-equipment-sound-with-the-description-from-the-prior-service-visit.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| multimodal-5 | Which painting appears in this family photograph? | [Which painting appears in this family photograph?](../visual-evidence-and-household-observation/which-asset-appears-in-this-historical-photograph.md) | NEW PRIMARY ALIAS — Same historical-photo Asset identification; one primary explicitly includes paintings in family photographs. |
| multimodal-6 | Read this instrument or meter shown in the service photograph. | [Read this instrument or meter shown in the service photograph.](read-this-instrument-or-meter-shown-in-the-service-photograph.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| multimodal-7 | Compare the visible reading with the invoice or service record. | [Compare the visible reading with the invoice or service record.](compare-the-visible-reading-with-the-invoice-or-service-record.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |
| multimodal-8 | What evidence across images and documents supports this conclusion? | [What evidence across images and documents supports this conclusion?](what-evidence-across-images-and-documents-supports-this-conclusion.md) | NEW PRIMARY — Distinct requested experience; scoped retrieval/comparison and its uncertainty, source and authority limits are captured without a mechanism. |

## Future questions

**OPEN ARCHITECTURAL QUESTION:** How could the household inspect this bounded experience, its evidence gaps and source lifecycle without assigning new authority or selecting a mechanism? Promotion requires [separate governed review](../README.md#promotion). Issue #1 remains OPEN; this increment awaits Owner acceptance and does not resolve the separate publication-alignment disposition.
