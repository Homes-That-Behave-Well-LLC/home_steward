# Derived knowledge lifecycle

> Proposed canonical requirements; awaiting Owner acceptance. Deletion propagation is **not implemented**.

Derived representations include extracted text, OCR, chunks, embeddings, vector indexes, summaries,
classifications, candidate relationships, inferred associations, memories, cached evidence and
generated narratives.

## Inheritance principle

Derived knowledge inherits source sensitivity, locality, authorization, purpose, retention and
lifecycle requirements unless separately governed. A transformation does not declassify data.
Combining sources must satisfy the most restrictive applicable constraints; it does not merge grants.

An authorization to store originals does not automatically authorize embeddings or long-lived memory.
Generated text can reveal its sources and requires audience evaluation.

## Required lineage

Reference authoritative source/version, grant/purpose, transformation/model/index version, derived
object location, beneficiaries, timestamps/freshness and applicable retention/deletion/hold rules.
Do not invent new permanent record identifiers or retention periods in this baseline.

The private-AI platform must not become the sole owner. Where practical, derived information must be
reconstructable from originals, explicit configuration and governed relationship records. Portability
must preserve lineage and permissions; exporting an unscoped vector dump is not sufficient.

## Events requiring a defined outcome

Source change/removal; access revocation; consent withdrawal; expiry; person/profile removal;
correction of a false inference; platform/model replacement; backup/restore; lawful governed hold.

Required surfaces include chunks/indexes, embeddings, memories, summaries, caches, replicas, paired
clients, exports and restored backups. A restored snapshot must not resurrect revoked access.
Deletion and Preservation Hold must follow the existing responsible owner's governance, not a new
central BehavesWell Extended Intelligence history/hold authority.

## Open implementation questions

How are derivations located and invalidated across providers? How is revocation enforced on offline
nodes? What deletion evidence is sufficient? What persists in backup and for how long? Which records
must be preserved for governed explanation without raw prompt/source retention? How are obligations
and privacy resolved when a source has its own legal hold?

Fail safely where a protected derived artifact's permission is uncertain. This document does not
claim a completed deletion-propagation mechanism or legal compliance certification.
