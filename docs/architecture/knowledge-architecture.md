# Knowledge architecture

> Proposed canonical baseline; awaiting Owner acceptance. Consumes accepted DL-81/DL-82/DL-131.

## Knowledge classes

| Class | Source of authority | Home Steward treatment |
|---|---|---|
| Governed Home definitions/relationships | Foundation/responsible HTBW owner | Consume by stable/versioned reference, never reconstruct a competing catalog |
| Current/historical Facts | Truth | Preserve time/quality/validity; do not override with model output |
| Household documents/records | Authoritative original source and its owner | Retrieve only approved portions; cite source/version/date |
| Public/external knowledge | Cited external source | Label external, assess currency/ambiguity; never automatically publish as HTBW Fact |
| Derived representations | Source-governed derivation | Preserve lineage, scope, lifecycle and reconstruction |
| Candidate relationships/interpretation | Inference, not authority | Label candidate; seek separately governed promotion |

## Provider-neutral path

Authoritative source -> authorized connector/query -> parsing/OCR/extraction -> references and
classification -> derived indexes/embeddings -> scoped retrieval -> replaceable reasoning ->
provenance-aware result -> responsible HTBW capability -> disclosure/action governance.

Not every request traverses every stage. Direct HTBW answers take the simpler authoritative path.
Retrieval is not evidence of disclosure permission. Original sources remain the source of record.

## Proposed result requirements

Carry the request/correlation reference, source classes and exact references where available, evidence
dates, freshness/gaps, interpretation versus fact, uncertainty, candidates/proposals, and locality
and authorization evaluation references. Do not duplicate the Decision Trace or store unlimited raw
prompts. Exact transport/schema identifiers and serialization remain open.

Conflicting documents remain conflicting. A recent-looking retrieval hit is not necessarily current;
a chunk without source identity/version is insufficient provenance.

Prompt injection in source documents is untrusted content, never an instruction to alter scope,
invoke tools or disclose other sources. Enforcement must be outside the model.

## HTBW Explainability and Home Steward investigation

**HTBW Explainability:** "Explain this governed event or non-event."

**Home Steward investigation:** "Reason across multiple governed events, logs, changes, documents,
time periods and other authorized evidence to help the household understand patterns, trends,
hypotheses, consequences and unresolved questions."

This distinction is about the work required, **not a prohibition on native historical queries**.
Accepted HTBW Explainability already supports time ranges, historical Facts, exact-version
reconstruction, cross-Room traces and bounded correlation/causation scopes. A native historical
answer or straightforward retained-record query does not require Home Steward. Home Steward adds
interpretation and cross-source synthesis; it never takes over those accepted retrieval paths.

The existing Decision Trace remains the Explainability spine:
trigger -> facts used -> identity evidence/assertion -> capability availability ->
Operational Trust evaluation -> conflict resolution -> decision -> action or non-action ->
observed outcome -> explanation.
This is a conceptual reading path, **not a replacement for the existing 21-field model**.
The trace remains authoritative for the governed decision it records, not proof of every physical
effect. Successful command issuance does not establish an observed outcome.

Concierge composes the trace from its owners' contributions. Persisted content is the accepted
Explainability Record, not a second Home Steward history. The existing `outcome_generated` /
`on_demand_decision_trace` origins, new-record rules, audience-governed Assist projections and
household-configured retention remain unchanged. No new trace fields, origin, reconstruction store,
retention duration or indefinite shadow summary is introduced.

### Evidence and epistemic rules

A faithful explanation may be incomplete. A plausible account unsupported by evidence is not an
explanation. **"I don't know" is a valid governed answer.**

| Evidence / reasoning class | Required distinction |
|---|---|
| Observed fact / observation | What an identified source actually reported, at its supported scope; not automatically a Truth Fact |
| HTBW Historical Fact | Truth-owned statement/confidence/provenance/freshness and exact historical policy; never current or actionable |
| Decision Trace evidence | Recorded governed evaluation, exact versions, decisions and observed/unknown outcome |
| HA log evidence | Separately authorized operational report; not automatic HTBW Truth, diagnosis or an original trace |
| Configuration evidence | Exact governed version/Change Record with Effective and Recorded Time; a raw state transition is not a Change Record |
| Service / document evidence | Source/date/model/revision and observed, attested or recommended scope |
| External evidence | Explicitly permitted public source, applicability and date; no private query leakage |
| Statistical pattern | Computation over a named eligible sample/window/denominator, with coverage and uncertainty |
| Correlation | Supported association, not causation; timing/shared dependency alone is insufficient root-cause evidence |
| Inference | Stated reasoning from cited evidence, not a new Fact or authority |
| Hypothesis | A possible explanation needing discriminating evidence, not a model-generated diagnosis |
| Unresolved ambiguity | Missing, contradictory, redacted, expired or never-retained evidence stated openly |

Every investigation retrieves the minimum authorized evidence for its question. Preserve source
identity/version, event-time precision, clock uncertainty, comparison windows, units, denominators,
deduplication and gaps. Distinguish first observed/retained evidence from actual onset; do not average
Truth or Identity confidence bands into probabilities. Ordinary non-actions and permitted manual
overrides are not automatically failures.

Native HA history/logs remain source-owned. Home Steward must not automatically copy whole streams,
preserve indefinite raw-log memory by default, re-derive competing Fact history, reconstruct expired content by invention,
or bypass an expired Explainability record through a retained shadow narrative. Derived summaries
inherit source authorization, sensitivity, locality and lifecycle; retention/deletion mechanics for
future log-derived data remain unimplemented.

Source times and presentation use HTBW's existing UTC/household-local/IANA conventions, not an
invented timestamp format, offset or precision.

Classify source/Person/actor reconstruction scope before protected assembly under existing HTBW
historical-access governance; generic Room Help or General Questions never bypass that path.
Access, disclosure and endpoint eligibility remain independently governed. Technical reliability
and friction analysis must not evaluate or rank people, infer human worth, or create performance profiles.

All proposed investigation, review, KEEP / ADAPT / REMOVE dispositions and corrective actions return
through the responsible HTBW capability, Operational Trust and Concierge. Home Steward may not
autonomously alter policy/preferences, disable integrations, remove automations, change Stewardship
obligations, roll back software, restart infrastructure, replace devices, schedule service or contact
vendors. Tools, model confidence and household confirmation of evidence are not those permissions.

### Accepted authority references

Consume current accepted
[Explainability](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/explainability.md),
[Decision Trace](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/models/decision-trace.md),
[historical retrieval DL-130](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-governed-historical-retrieval-and-access.md),
[amended retention DL-137](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-explainability-persistence-and-retention.md)
and [presentation DL-140](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/architecture/adr-explainability-presentation-and-assist-interaction-path.md).
The source [Decision Ledger](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/governance/decision-ledger.md)
and [glossary](https://github.com/Homes-That-Behave-Well-LLC/homes_that_behave_well/blob/main/docs/models/glossary.md)
remain authoritative; this proposed consumer document does not amend them.

### Investigation scenario navigation

All thirteen new scenarios apply these rules and the
[future log-source requirement](governed-source-connections.md#future-governed-ha-logs-and-history).

- [Recurring late behavior](../scenarios/why-has-this-been-happening-lately.md)
- [Problem onset](../scenarios/when-did-this-problem-start.md)
- [Meaningful Home changes](../scenarios/what-changed-in-the-home.md)
- [Reliability trend](../scenarios/is-this-getting-worse.md)
- [Preference review](../scenarios/why-do-i-keep-overriding-this.md)
- [Apparently abandoned technology](../scenarios/what-technology-have-we-stopped-using.md)
- [Recurring technical failures](../scenarios/what-keeps-failing.md)
- [Related problems](../scenarios/are-these-problems-related.md)
- [Update comparison](../scenarios/did-the-update-make-things-worse.md)
- [Early signs of trouble](../scenarios/is-anything-showing-early-signs-of-trouble.md)
- [Lived-outcome review](../scenarios/did-the-fix-actually-work.md)
- [Technology friction](../scenarios/what-keeps-making-us-intervene.md)
- [Evidence limits](../scenarios/what-dont-you-know.md)
