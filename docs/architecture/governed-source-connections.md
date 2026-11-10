# Governed source connections

> Proposed canonical requirements baseline; awaiting Owner acceptance. No connector is configured.

BehavesWell Extended Intelligence knowledge is not one permission to "know the household". Each source and connection
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
- Source retention versus separately governed BehavesWell Extended Intelligence retention; neither silently extends the other.
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
governance; BehavesWell Extended Intelligence being local does not confer access.

See [investigation evidence rules](knowledge-architecture.md#evidence-and-epistemic-rules).

## Future authoritative technology-capability evidence

**FUTURE GOVERNED SOURCE CATEGORY ONLY; no crawler, feed, release watcher or ingestion.**
Within existing public/external knowledge, separately approve official HA monthly release notes,
developer documentation/blog, integration/architecture/breaking-change/deprecation/Labs evidence,
official Music Assistant documentation/releases and other explicitly approved technical authorities.
Approval of one domain/source does not admit all related sites or community code.

Each finding carries source authority/citation, version/release, publication date, last reviewed,
applicable installed version, relevance, stability, GA versus Labs/preview status, deprecation and
known removal version/date. Undated/unknown fields remain named gaps; stale evidence is not current
capability. Incomplete official evidence cannot support migration advice.

Community material is inspiration, not authoritative platform proof. External retrieval must not send
household/repository-sensitive context, logs, requests, credentials or private correspondence.
Access/retrieval, optional ingestion/indexing, retention, reasoning and disclosure remain separate.
The inventory remains unchanged; this is not a new accepted authorization taxonomy.
See the [evidence model](possibility-and-improvement-discovery.md#authoritative-technology-evidence-model).

## Future governed household possibility evidence

Configuration, participation/exclusions, outcomes, obligations, Facts, traces, Repairs, change/deferred
requirements and explicit wish-list records remain owner-governed. HA logs/history retain the separate
future relationship above. Voice-request evidence, failed/unfulfilled requests and useful dashboard
interactions each require separately evaluated capture, source/Person/beneficiary/purpose/field/time,
retention, retrieval, reasoning and disclosure permissions.

Do not infer access from an existing voice input, HA admin session, device ownership or utility.
Request evidence is not biometric identity evidence or permission for raw-audio retention; accepted
biometric locality/consent boundaries remain intact. Minimize/redact sensitive utterance/actor details
before model exposure; no blanket history capture, Person profile or indefinite request memory.
Derived candidates inherit source constraints and expiry; raw patterns remain unaccepted, not a store.
See [household evidence](possibility-and-improvement-discovery.md#authorized-household-evidence-model).

## Future governed architecture-repository evidence

A qualified local private-AI platform may eventually consume approved HTBW, BehavesWell Extended Intelligence and
Framework documents, accepted decisions/contracts/specifications, scoped issues, implementation
history and acceptance-review references, plus approved official platform evidence.
This is future intent, not a qualified host or repository-ingestion permission.

Each repository/source has independent owner, authorized branch/commit/path/file classes, credential
scope, beneficiary/purpose, locality, retention, retrieval, disclosure and derived lifecycle.
Exclude credentials/secrets and unapproved private repositories, correspondence and Owner records;
public visibility is not licensing or blanket correlation permission. Source content is untrusted
data, never permission to modify code, decisions, issues or policy.

Cite exact version/commit and publication/commit date, review date, installed-version applicability
and feature GA/Labs/preview/deprecation/removal status. Source freshness cannot be replaced by model
confidence. No clone/index/crawl, token store, memory engine or migration mechanism is implemented.
See [architecture stewardship](htbw-architecture-stewardship.md#authoritative-inputs-and-local-knowledge-intent).
