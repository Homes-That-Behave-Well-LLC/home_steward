# Sonos MCP

> RESEARCH INCOMPLETE. Public-source bootstrap reviewed 2026-11-07; no service connected.

## Official technical / legal sources

[Sonos engineering blog](https://tech-blog.sonos.com/posts/sonos-27mcp/) and
[MCP Addendum](https://www.sonos.com/en-us/legal/mcp-addendum).

The reviewed offering, **Sonos 27mcp**, is an **official Sonos-operated hosted MCP service**, not
a third-party local-only server. Third-party AI clients authorize against a Sonos account.
Docs describe OAuth Dynamic Client Registration and standard discovery.

The terms identify Early Access, English-only at review, with no guarantee of continued tools,
availability or identical assistant behavior. Sonos says it receives resulting instructions rather
than the assistant's conversation; this is vendor policy, not measured payload/retention evidence.

## Fit / unknowns

Hosted service is an external relationship and cannot be silently counted as local inference or
local-only control. Tool payload/privacy, account scopes, permission mapping, failure behavior,
retention, service dependency and stability require future review.

No alternative local MCP implementation was verified in this bounded pass. Do not fabricate one
or classify the official service as a community bridge.
HTBW authorization remains independent of Sonos OAuth/client tool availability.
No OAuth connection, MCP setup or playback action performed.
