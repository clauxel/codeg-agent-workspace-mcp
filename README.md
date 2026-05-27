# CodeG Agent Workspace

See and hand off every coding agent session in one workspace.

CodeG Agent Workspace is a paid hosted remote MCP for CodeG. It exposes Streamable HTTP tool calls, bearer-token access, public server-card metadata, usage logs, and receipt-oriented JSON for AI agent workflows.

## Public Endpoints

- Website: https://codegworkspace.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- MCP endpoint: https://codegworkspace.clauxel.com/mcp
- Server card: https://codegworkspace.clauxel.com/server-card.json
- Registry name: `com.clauxel.codegworkspace/codegworkspace-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `register_agent_session`
- `read_workspace_roster`
- `write_handoff_note`
- `export_session_summary`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://codegworkspace.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27
- Pricing: https://codegworkspace.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605r27#pricing
- Server card: https://codegworkspace.clauxel.com/server-card.json
- MCP endpoint: https://codegworkspace.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
