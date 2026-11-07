# HTBW integration contract

> Proposed integration boundary; **not an accepted transport/schema or implemented API**.
> Subordinate to accepted DL-131/DL-81/DL-82/DL-93 and HTBW responsibility contracts.

## Request inputs

The responsible capability supplies only authorized context: request/correlation reference,
effective Person and purpose, relevant Room context, governed source references, eligible fields,
retrieval/reasoning limits, locality constraints, evidence freshness and allowed output/proposal scope.
Room is context, not Home Steward authorization owner.

Use native stable/versioned identifiers; no display-name, vendor, IP or runtime-search identity.
Existing Foundation `(room_id, function)` relationships may be consumed by an authorized integration;
they are not recreated as a Home Steward endpoint map.

## Results

Return an answer with source-class provenance, dates/gaps, uncertainty, candidate relationships and
clearly separated proposed actions. Return a named unavailable/unsupported/restricted outcome where
needed, not an invented answer or a silent cloud fallback.

Results do not mutate HTBW state, grant permission, publish Truth or independently compose the
Decision Trace. Exact field names, versions, API/transport and correlation format remain open.

## Integration requirements

Assist remains the household surface; Concierge/responsible capabilities remain orchestrators.
Check the effective Person's independent Home Steward gate; do not bypass denial through General
Reasoning. Provider substitution never changes governance.

Authentication, timeouts, cancellation, rate limits, least-privilege service identities, reauth,
diagnostics/redaction, unavailable states and tests must be designed before executable work.
MCP and OpenAI compatibility are candidate transports, not selected contracts or permissions.

## Evidence / deferred implementation

HTBW #201 established a package, official HA tests and guarded Windows deployment. It did not
implement this contract or authorize runtime work in this repository.
See [HA interface research](../research/home-assistant-ai-integration-surface.md).
