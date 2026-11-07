# MyOtto.ai / Otto

> RESEARCH INCOMPLETE. Public-source bootstrap reviewed 2026-11-07; grouped [#4](https://github.com/Homes-That-Behave-Well-LLC/home_steward/issues/4).

## Official sources

[Product](https://myotto.ai/), [Otto One](https://myotto.ai/otto-one),
[hardware tiers](https://myotto.ai/hardware), [runtime](https://myotto.ai/runtime),
[privacy](https://myotto.ai/privacy/otto), [credentials](https://myotto.ai/help/safety/privacy-and-credentials).

## Official technical documentation / claims

The vendor's hardware page says **Otto One inference runs in the cloud**, while files, credentials
and tasks reside locally. Intel N95 / 8 or 16 GB DDR4 is the published base tier.
"Own your AI" does not mean that tier provides local inference.

**Otto Pro**, Coming Soon, is described as supporting on-device quantized inference with AMD Ryzen
AI 7 350 and 32/64/96 GB memory, with local/cloud task routing. Availability and performance are
vendor claims, not measured capacity.

Runtime is described as built on OpenClaw, with a gateway/routing layer. Credential help explicitly
mentions custom APIs and MCP servers. Under the published Integrations model, every agent on a
device can use listed apps; that is not evidence of per-person/per-agent least privilege.
The OpenClaw project's behavior/license was not evaluated here.

## Privacy evidence / unknowns

Vendor policy describes local device content and encrypted app-device relay, but explicitly separates
that transport protection from cloud inference/integration disclosures. Local storage is not local
processing. Full analytics and derived retention/deletion sections require deeper research.

Enforceable local-only Pro routing, per-person sources, prompt/memory lifecycle, export/erase,
credentials, telemetry, update/vendor exit and app extension controls remain unresolved.
Base Otto One's published cloud inference is incompatible with the intended local-only profile on
its face; **no final candidate qualification outcome is issued in bootstrap**.

No hardware purchased, software installed or network/API tested.
