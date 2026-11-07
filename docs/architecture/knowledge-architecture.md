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
