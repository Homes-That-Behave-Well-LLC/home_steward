# Music Assistant MCP

> RESEARCH INCOMPLETE. Public-source bootstrap reviewed 2026-11-07; interface research, no setup.

## Official technical documentation

[Official FastMCP plugin](https://www.music-assistant.io/plugins/fastmcp-server/),
[official organization](https://github.com/music-assistant).
Docs describe library/queue/playback/player tools, revocable per-client tokens, granular
browse/control/queue/playlist/settings permissions, optional token-audience enforcement and allowed Origins.
The plugin is explicitly early-stage. Current documented controls are not tested HTBW governance.

## Separate community implementation

[davidpadbury/music-assistant-mcp](https://github.com/davidpadbury/music-assistant-mcp) is independent,
MIT-licensed and uses the Music Assistant WebSocket API. Its maintenance/auth/tool scope is not
automatically the official plugin's posture. Do not conflate the two.

## Unknowns and boundary

Exact endpoint/version, credential storage, exposure, telemetry, retention, person/room scope and
read-versus-action denial require evidence. Cloud music-provider connections must be separately
admitted, not assumed local because the MCP endpoint is local.

HTBW governs request context/permission; Music Assistant can execute eligible music operations.
Tool presence never creates permission or proves playback occurred.
No MCP server/plugin installed or music action tested.
