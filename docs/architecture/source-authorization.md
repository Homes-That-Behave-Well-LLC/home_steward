# Source authorization

> Proposed canonical requirements; awaiting Owner acceptance. Existing HTBW owners remain authoritative.

## Evaluation boundaries

1. Resolve the effective Person through Identity and check the independent Allow Home Steward gate
   under DL-93. Room context is not that gate's owner.
2. Obtain applicable HTBW policy and consent scope for this source, purpose and operation.
3. Admit only the approved account/namespace/fields to the connector.
4. Independently authorize parsing, indexing, embedding and derived retention.
5. Filter retrieval for the requester and purpose **before** model exposure, including caches.
6. Independently evaluate the answer's disclosure to the actual audience/output surface.
7. Return proposals for separate HTBW action/confirmation evaluation.

These are required separation points, not an implemented permission engine. Neither a prompt nor
an LLM's promise to ignore restricted material substitutes for enforced scope.

## Person-scoped sources

A household member's mailbox, calendar, finances, health documents or personal files remain scoped
to that person and explicitly approved beneficiaries/questions. Household membership, shared Wi-Fi,
an administrator account or possession of a bearer credential does not create universal access.

Policies must support source owner, beneficiaries, question categories, prohibited disclosures,
purpose limitation, separate write/action authority, attributable revocation, retention/deletion
and person-specific restrictions.

## Revocation and uncertainty

When authorization cannot be determined, do not expose the protected content or fall back to another
Person's account. An already-built index does not preserve an expired grant.

Revocation must apply to connector access, retrieval, cached answers and derived representations.
Exactly how deletions, backups, offline nodes and holds are reconciled remains an implementation
question, not a solved feature. See [derived lifecycle](derived-knowledge-lifecycle.md).

Foundation holds consent records; Identity owns their lifecycle; Operational Trust evaluates policy
and permission for this request. BehavesWell Extended Intelligence owns none of those decisions.
