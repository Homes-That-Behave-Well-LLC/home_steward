# Ghost Core

> **RESEARCH INCOMPLETE.** Public-source bootstrap reviewed 2026-11-07.
> Dedicated [#3](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/3).
> No selection, purchase, partnership, install, API probe or inference benchmark.

## Sources and evidence

Official [Ghost home](https://ghost.ai/), [Core product and FAQ](https://ghost.ai/core),
[privacy policy](https://ghost.ai/privacy). The FAQ includes details not exposed by the site's
simplified text presentation; public page content, not private inquiry, is the evidence here.
Owner-supplied screenshots of the public Core specification tabs add product-claim evidence
for connectivity, power and physical specifications; they are not independent measurements.
The screenshots themselves are not copied into this public repository.
No independent observations were collected.

## Official product claims (not independently verified)

- Turnkey personal AI computer, on-device inference, local memory/context and 24x7 proactive agents.
- Advertised $3,499, no subscription, Sold Out / first batch ships October 31 at review time.
  These are time-sensitive vendor statements, not confirmation of delivery or availability.
- NVIDIA RTX PRO 4000 Blackwell SFF, 24 GB GDDR7 ECC, 432 GB/s; AMD Ryzen 5 9600X
  (6 cores / 12 threads); 64 GB DDR5; 1 TB NVMe.
- Vendor-listed models: Qwen 3.8-Next, Qwen 3.8-27B, Gemma 4-31B, Muse-Glimmer-30B.
  Names/capacity/quality were not independently validated.
- The public performance tab advertises **770 AI TOPS**. Precision, benchmark conditions, sustained
  throughput and household/coding performance are not established by that number.
- The public connectivity/power tab advertises **2.5 Gb Ethernet + Wi-Fi**, Bluetooth and
  **205 W maximum draw**. Ethernet is now documented as a vendor claim, no longer an unknown
  advertised feature. Link speed, local isolation and actual electrical consumption remain untested.
- The public physical tab advertises **2.8 in W x 15.0 in H x 8.7 in D**, approximately **11 lb**.
- The product page advertises **1-year warranty**, **30-day return** and **free shipping for batch 1**.
  Eligibility, detailed terms and current availability require review; these are not independently
  confirmed commercial guarantees.

Maximum draw is not idle or average consumption. At the advertised 205 W continuously, the
arithmetic ceiling would be about 1,796 kWh/year or 8,979 kWh over five 365-day years, excluding
other equipment. This is a conditional calculation, not a measured energy estimate, purchase
recommendation or five-year TCO. Actual duty cycle, tariff, noise, thermals and Owner time remain open.

## Official API / developer claims

The public FAQ states an endpoint compatible with the **OpenAI Responses API**, custom-endpoint
use with OpenCode, OpenClaw and Codex, and own apps/scripts/agents without per-token **local
inference** fees.

This is a concrete vendor claim worth research. It is not a verified API reference, authentication
contract, model enumeration, version-stability guarantee, Chat Completions/embeddings compatibility,
HA integration or benchmark. Hardware and "OpenAI compatible" slogans are insufficient qualification.

The FAQ says local AI/memory can work without cloud; internet is needed for web search, email and
over-the-air updates. Research must distinguish external source access from remote inference.

## Privacy-policy evidence (vendor-authored disclosures)

The policy is more specific than general on-device marketing:

- Conversational AI and memory are described as running/stored on hardware with no remote AI fallback.
- Online features can send task information to external services.
- Ghost-managed gateway services may forward requests/responses; claimed absence of content storage
  at Ghost's gateway does not settle third-party retention or network disclosure.
- Bring-your-own-key direct connections can avoid some managed routing; not all Ghost-managed
  services necessarily disappear.
- Account identifiers, access credentials, permissions and connection records may be processed.
- Browser import can include passwords and signed-in sessions, enabling account access/actions.
- Memory may persist independently after original-source removal and can be inaccurate.
- Paired-device/local/cloud-backup copies may remain after Core erasure.

These disclosures are material to scoped egress, person authorization, credential handling and
derived deletion. They must be reconciled with the local-only qualification profile; this baseline
does not issue a final disqualification before accepted #2 method and evidence review.

## Generic Ghost Home Assistant integration (separate potential work)

A native generic provider integration could expose authenticated configuration, capability/model
enumeration, Conversation and possibly supported AI Task functions, health, diagnostics/redaction,
reauth and unavailable behavior. Actual APIs must support each function.

That does **not** create Home Steward's source governance, Person capability gates, Truth ownership,
Continuity, action authority or native HTBW relationships.
See [HA implementation/upstream research](home-assistant-ai-integration-surface.md).
No integration or client package is implemented or selected.

## Open technical questions

| Area | Evidence needed |
|---|---|
| API | Published schema/version, auth/TLS, network binding, model list, streaming/errors, Responses versus other endpoints |
| HA fit | Native Conversation/AI Task capabilities, async client, diagnostics, lifecycle and unavailable behavior |
| MCP / tools | Host/client roles, enumeration, auth, read/action scopes, how tools remain under HTBW authority |
| Extensibility | Own application/container/plugin support, governance hooks and replaceability |
| RAG / context / memory | Source APIs, scoped retrieval, derived lineage, correction, export/delete and retention controls |
| NAS | Explicit share/path/account scope, local retrieval and document lifecycle |
| M365 / email / calendar | Person/account/category/purpose isolation; retrieval distinct from send/schedule authority |
| Financial / banking / insurance | Minimized read scope, no transaction or binding authority, egress and retention |
| Ethernet / networks | Advertised 2.5 Gb wired connection's observed behavior, isolation/local-only topology and deployment controls |
| Local enforcement | Actual egress endpoints/data flows, no silent inference fallback, optional updates/support/gateway dependencies |
| Credentials / accounts | Secure storage, minimal scopes, rotation/revocation and imported-browser-session hazards |
| Lifecycle | Original/derived/paired-client/backup inventory; revocation, secure erasure and restored-backup behavior |
| Multi-person | Identity/source/answer audience isolation, shared output surfaces and memory contamination prevention |
| Vendor exit | Offline use, activation/licensing, model/app export and recovery if vendor disappears |
| Operations | 24x7 thermals/noise/power, signed updates, rollback, security audits/support content access |
| Home Steward fit | Enforceable local-only source/person/derived governance and external HTBW authority, not just chat |
| HTBW development inference | Coding workload, context/structured outputs, latency/concurrency and cost, separately benchmarked |

## Inquiry and next step

The Owner initiated a technical inquiry. No email, contact details, private correspondence or alleged
vendor response is published. This does not imply partnership, endorsement or upstream collaboration.

Public evidence may be expanded under #3; no final qualification before
[#2](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/2) is Owner-accepted.
No qualification/Reference Home/development-inference test started.
