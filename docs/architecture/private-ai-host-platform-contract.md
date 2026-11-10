# Private-AI host platform contract

> Proposed canonical requirement; awaiting Owner acceptance in [#2](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2).

BehavesWell Extended Intelligence should operate above a qualified, replaceable private-AI platform supplying commodity
infrastructure, not require HTBW to build a generic AI distribution.

## Platform services

Hardware abstraction; inference/model management; parsing/OCR; embeddings/vector storage; RAG;
controlled memory; agent runtime/scheduling; authenticated MCP/application APIs; administration,
health, updates, backup and recovery.

Services may be composed across explicitly admitted local hosts/namespaces. Their presence does not
mean all are required, authorized, implemented or equally trustworthy.

<a id="home-steward-obligations"></a>
## BehavesWell Extended Intelligence obligations

Consume governed household knowledge, scope requests, preserve provenance and uncertainty, maintain
source/derived lifecycle requirements and return proposals to HTBW. No new original-data or
responsibility authority.

## Platform obligations

Technical local-only enforcement; independent source/person permissions; secure credentials;
bounded authenticated interfaces; explicit data flows/logging; export/reconstruction/erasure;
support/update transparency; usable offline/vendor-exit posture; backup/restore that preserves
revocation. Model prompts alone cannot implement these guarantees.

A missing mandatory service yields a named unavailable extension. Optional features cannot silently
become prerequisites for deterministic HTBW behavior.

Qualification uses [hard gates](../platforms/qualification-gates.md) before weighted comparison.
No candidate meets this contract by assertion, and no platform is selected in this baseline.
