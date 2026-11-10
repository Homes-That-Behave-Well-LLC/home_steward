# Inference provider contract

> Proposed canonical requirements; API/schema/provider not selected.

Required future contract evidence: documented endpoint/version, supported request/response types,
authentication, injected client/timeouts/cancellation, model enumeration, capabilities, context/token
limits, streaming, errors, tool semantics, structured outputs, health and deterministic unavailable behavior.

OpenAI Chat Completions, Responses, embeddings, HA Conversation and AI Task are **different**
interfaces. Compatibility with one does not prove another. A model name does not prove a capability.
Tool results, retrieved text and provider instructions never create HTBW authority.

Local-only processing must be enforceable; remote/cloud fallback cannot be automatic. Report the
actual provider/model and limitations, not a silent substitute. Do not log secrets or retain unlimited
raw prompts/responses. Carry minimal provenance/configuration versions for explainable results.

Household Knowledge Provider/BehavesWell Extended Intelligence is distinct from configured General Reasoning. Independent
Person gates Allow Home Steward / Allow General Questions remain YES/NO, without implied permission.
Accepted General Reasoning resolution remains **Person -> Integration-default -> unavailable**.
No Room provider-selection or authorization step and no runtime provider discovery/fallback to BehavesWell Extended Intelligence.

A generic API client never grants HTBW knowledge access or Home control. Exact SDK and transport
choice remain deferred. See [HA research](../research/home-assistant-ai-integration-surface.md).
