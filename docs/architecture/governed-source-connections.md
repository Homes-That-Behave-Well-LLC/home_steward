# Governed source connections

> Proposed canonical requirements baseline; awaiting Owner acceptance. No connector is configured.

Home Steward knowledge is not one permission to "know the household". Each source and connection
relationship is independently authorized.

## Independent dimensions

Source authorization; connection authorization; ingestion; parsing/OCR; extraction/indexing;
embedding; retention; retrieval; disclosure; person scope; application scope; reasoning use;
proposal authority; action authority.

Granting one dimension never grants the others. Credentials are a mechanism, not the grant.

## Initial source classes (inventory, not an accepted authorization taxonomy)

| Source class | Boundary to preserve |
|---|---|
| HTBW / HA governed Home knowledge | Native authority and explicit HTBW exposure |
| NAS / connected household storage | Approved namespace, not every share or account |
| Asset documents | Native Asset/document relationship and original-source lifecycle |
| User / service manuals | Exact model/revision and document permissions |
| Service / maintenance records | Evidence of service, not automatic obligation satisfaction |
| Email | Person/source scope; no implied send/reply/delete authority |
| Calendar | Approved event fields/categories; no implied scheduling |
| Financial information | Minimized fields and beneficiaries; no payment permission |
| Banking information | Read scope separate from transfer/account actions |
| Insurance information | Dated evidence, not binding coverage authority |
| Health / care information | Person-specific consent, purpose and restricted disclosures |
| Photographs / recordings | Capture/association/retention permission and third-party privacy |
| Public / external knowledge | Explicit external query scope; no private context leakage |
| Future source types | Unadmitted until explicitly evaluated |

Every connection must declare endpoint/account/namespace, owner, authorized beneficiaries, allowed
question categories, prohibited disclosures, purposes, permitted transformations, freshness,
revocation, retention/deletion/hold behavior, locality and independent action scope.

Fine-grained category names, canonical record shape and enforcement adapters remain
[open](../governance/open-questions.md); this inventory does not settle DL-131's deferred taxonomy.

Read access is not write authority. Financial knowledge is not payment/transfer authority.
Email access is not agreement, commitment, send or approve authority.

## Future governed HA logs and history

**FUTURE GOVERNED SOURCE REQUIREMENT ONLY; no log access, ingestion or connector is implemented.**

Within the existing HTBW / HA source family, operational HA logs/history require a **separate**
governed source relationship. Permission for HTBW's governed knowledge is not permission for every
HA log, Recorder row or entity/person history. This preserves the inventory above and does not
create a new accepted taxonomy or authorization mechanism.

HA logs are operational evidence, not automatically Truth, a physical diagnosis or the Decision
Trace for an evaluation HTBW did not perform. Native history remains native/source-owned and is
consumed by eligible reference; no second Recorder or competing Fact history is proposed.

Future design must determine, before implementation:

- Which log/history classes, integrations, entities, fields and time windows are eligible.
- Query-based access versus ingestion, with no assumption that wholesale ingestion is desirable.
- Source retention versus separately governed Home Steward retention; neither silently extends the other.
- Sensitivity, Person/actor privacy, source-existence disclosure and permitted audiences/endpoints.
- Secret/credential/account/identifier redaction before retrieval, reasoning and any disclosure.
- Minimum-needed retrieval, access identities, field filters and bounded resource use.
- Provenance, event/record times, clock precision, deduplication and coverage of derived summaries.
- Derived authorization/locality/retention, correction, revocation and deletion across caches/backups.
- Evidence that was never retained, has aged out or is redacted, including honest gaps and unavailable references.
- The operational-only authority of logs versus Truth-owned Facts and recorded Decision Trace decisions.
- Performance implications: query volume, history scans, storage/backup growth and effect on native operation.

No query API, ingestion process, retention duration, database, schema or deletion engine is chosen.
Existing HTBW Explainability retention, reconstruction routing and source ownership remain unchanged.
Do not assume indefinite raw-log memory or create shadow summaries of expired Explainability content.
Every proposed investigation/action remains subject to current source, Person and Operational Trust
governance; Home Steward being local does not confer access.

See [investigation evidence rules](knowledge-architecture.md#evidence-and-epistemic-rules).
