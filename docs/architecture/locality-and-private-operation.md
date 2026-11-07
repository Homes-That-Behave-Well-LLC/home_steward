# Locality and private operation

> Owner-directed local qualification profile; proposed canonical baseline awaiting review.
> Accepted DL-131 locality and broader HTBW provider options remain unchanged.

## Canonical working definition

Local means processing, storage, derived knowledge, inference, retrieval, embeddings, RAG, memory and
approved service relationships remain inside the household-controlled and governed Home network
boundary.

It need not be the HA host, HAOS, HTBW Integration, same computer, process, container or VLAN.
A separate private-AI appliance in that boundary can be local.

## Explicitly governed relationships

HTBW/HA -> Home Steward; Home Steward -> private-AI appliance; appliance -> approved NAS namespace,
local model, embeddings service, vector store, Music Assistant, local MCP service or another admitted
source/capability.

Physical presence inside the Home does not admit every service on a machine. Scope includes the
resource, namespace, service identity, account, API, connector and allowed operation.

## External sources versus local processing

Authorized public search or an external mailbox/banking source may require an explicit outbound
connection. It must declare what leaves and why. This is not permission for remote inference,
embedding or retention of household-sensitive content. External queries must omit protected context
unless its separate disclosure has been authorized.

The local qualification profile requires technical enforcement of local inference/storage and
scoped egress, no silent cloud fallback and no routine vendor-service dependency. An update/model
download is distinct from routine household operation and must not be used to conceal background
data transfer.

Broader HTBW General Reasoning permits configured household-approved cloud providers under DL-93.
This stronger Owner-directed profile does not erase those accepted options or automatically route
General Reasoning through Home Steward.

## Unavailable behavior

Report the unavailable extension and missing dependency. Preserve HTBW's authoritative definitions,
relationships, obligations, Truth, Identity, Continuity, Trust and deterministic behavior. No
unannounced remote fallback, weaker local impersonation or use of an unadmitted service.

Technical egress, DNS, support, telemetry and backup tests are proposed in
[evaluation method](../platforms/evaluation-method.md); none ran in bootstrap.
