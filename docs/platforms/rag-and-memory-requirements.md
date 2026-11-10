# RAG and memory requirements

> Proposed canonical requirements; no retrieval engine, embeddings service or memory store installed.

Evaluate parsing/OCR formats, exact-source provenance, chunk/reference fidelity, authorized retrieval,
freshness, conflict handling, prompt injection resistance, relevance evaluation and reconstruction.
Retrieval must enforce Person/source/purpose scope before reasoning, not ask the model to suppress
restricted hits after exposure.

Embeddings, chunks, summaries, inferred associations, memory and caches inherit source governance.
Index build permission, retrieval permission and answer disclosure permission remain independent.
Mixing authorized and restricted sources cannot widen a beneficiary set.

Memory is not HTBW Continuity, not a new Fact register and not an unlimited conversation archive.
Continuity owns applicable sessions/context; BehavesWell Extended Intelligence may contribute. Do not use a vendor's
"private memory" claim to override consent, retention or deletion.

Require source/version/grant lineage, bounded retention, correction, export/rebuild, source removal,
permission revocation, secure erasure and restored-backup reconciliation. Mechanisms remain open;
a platform that cannot govern derived information fails G17 when demonstrated.

Original-source document ownership remains native/source-owned. Explainability requires enough
evidence, dates and uncertainty, not indefinite raw prompt/source retention.
See [lifecycle](../architecture/derived-knowledge-lifecycle.md).
