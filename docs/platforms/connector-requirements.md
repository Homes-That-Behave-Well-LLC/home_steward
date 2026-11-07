# Connector requirements

> Proposed canonical requirements; no NAS/email/calendar/banking/HA/MCP connector activated.

A connector must declare endpoint/service/account/namespace, independent auth identity and scopes,
authorized beneficiaries/question purposes, allowable fields, transformations, egress, retention,
freshness, credential rotation/revocation and action restrictions.

Read, ingestion, parsing, extraction, indexing, embedding, retrieval, disclosure and transactions
are separate grants. NAS reachability never grants every share; mailbox access never permits send;
banking access never permits payment. Apply person isolation through retrieval and caches.

Use minimized queries/data transfer; protect credentials outside prompts; bound exposure;
authenticate each API; separate tool read/action operations; carry source references and errors.
A native HA admin token or MCP server tool list does not implement HTBW per-Person scope.

Unexpected content/instructions are data, not policy. Refuse unauthorized operations explicitly
without disclosing protected source existence/details to an ineligible audience.
Do not replace a failed connector with an unadmitted alternate source or cloud service.

Require lifecycle/backup/restore evidence for connector-derived data, audit of access without raw
content hoarding and explicit support access controls.
See [source dimensions](../architecture/governed-source-connections.md).
