# Home Assistant AI integration surface

> Official-source research, 2026-11-07. No integration implemented; no upstream acceptance claim.

## Official technical sources

- [LLM API](https://contributors.home-assistant.io/core/internals/llm-api/)
- [Conversation entity](https://contributors.home-assistant.io/core/entities/conversation/)
- [AI Task entity](https://contributors.home-assistant.io/core/entities/ai-task/)
- [MCP Server](https://www.home-assistant.io/integrations/mcp_server/)
- [MCP client](https://www.home-assistant.io/integrations/mcp/)
- [Integration manifest](https://contributors.home-assistant.io/core/integrations/manifest/)
- [Quality scale](https://contributors.home-assistant.io/core/quality-scale/)
- [Quality rules](https://contributors.home-assistant.io/core/quality-scale/rules/)
- [Dependency transparency](https://contributors.home-assistant.io/core/quality-scale/dependency-transparency/)

These are documented HA capabilities/rules, not evidence that Ghost/Home Steward implements them.
Current docs are observations, not a locked future API compatibility promise.

## Conversation / Assist

ConversationEntity adapts native requests/chat logs to a provider. HA owns conversation history;
a provider integration should not create a second history owner. HTBW Continuity still owns its
governed experience context. Assist remains the household surface; Home Steward stays behind it.

## AI Task

Documented one-off structured data, image generation/evaluation and attachment features depend on
actual provider support. OpenAI Responses compatibility does not prove every AI Task/Conversation
function, streaming mode, attachment or tool contract.

## Native LLM APIs

Docs distinguish `assist` (exposed entity/device control, no administrative actions) from
`homeassistant` (administrative registries/logs/config-entry access, admin only).
Integration `llm.py` tools and native option selection do not create HTBW authority.
Never infer all API modes or URLs are read-only.

## MCP direction and exposure

HA MCP Server allows external AI clients to call HA tools. HA MCP client lets a conversation agent
consume an external MCP server. Those are opposite directions.
Current server documentation describes admin-related requirements and configurable tool exposure,
including default broad/all tools. Audit the exact endpoint/options; native auth/exposure is not
HTBW per-Person permission, source scope, consent or confirmation.

## Generic Ghost integration versus Home Steward

A future generic Ghost provider could supply native config/auth/model enumeration, Conversation,
supported AI Task, reauth/reconfigure, health, diagnostics/redaction, unavailable behavior and tests.
It would not implement the full governed knowledge/action/source boundary.
The client/API must be documented and stable; "compatible" vendor FAQ is not sufficient.

## Core / Platinum prerequisites (not achieved)

Current quality-scale rules require Bronze for new integrations, and every lower tier for Platinum.
The rule list has Bronze 20, Silver 10, Gold 21 and Platinum 3 at review.
Silver includes >95% coverage and an integration owner. Gold covers translations, diagnostics,
Repairs/discovery/reconfigure as applicable. Platinum requires async dependencies, injected shared
web session support and strict typing.

Dependencies must have OSI-approved licensing, public source, public PyPI releases and tagged
public-CI publishing under HA dependency-transparency rules.
A future Ghost client likely needs a separately licensed async package/API, suitable tests,
maintainers and vendor technical collaboration. This documentation repository's unresolved license
does not meet a future Core dependency requirement.

## Unknowns / deferred decisions

The actual Ghost API schema/authentication/versioning, supported Conversation/AI Task functions,
appropriate async client, exact quality-rule applicability, maintainer commitment, license and
public publishing pipeline remain unknown or unverified. No interface is selected by this research.

No existing vendor client, API stability, public publishing workflow, collaboration, quality tier
or HA Core submission is assumed. No package/integration/runtime installed or test executed here.
