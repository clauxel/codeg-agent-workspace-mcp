# CodeG Agent Workspace

CodeG Agent Workspace is a hosted remote MCP for CodeG.

This repository is a public documentation project for CodeG Agent Workspace. Its structure follows the public documentation pattern used by [MiroFish](https://github.com/clauxel/MiroFish): a short front door, a clear reading order, practical guides, reference pages, and a public-safe boundary.

## Start Here

- Website: https://codegworkspace.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=readme_home
- Pricing: https://codegworkspace.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=readme_pricing
- Checkout: https://codegworkspace.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=readme_checkout
- Support: support@aigeamy.com

## Remote MCP

- Endpoint: https://codegworkspace.clauxel.com/mcp
- Server card: https://codegworkspace.clauxel.com/server-card.json
- Registry name: `com.clauxel.codegworkspace/codegworkspace-mcp`
- Tools: `register_agent_session`, `read_workspace_roster`, `write_handoff_note`, `export_session_summary`

## Reading Order

1. [Quickstart](guide/quickstart.md)
2. [Evaluation guide](guide/evaluation.md)
3. [Checkout and pricing](guide/checkout-and-pricing.md)
4. [Workflow notes](features/workflow.md)
5. [Security model](features/security-model.md)
6. [Public link reference](reference/links.md)

## Audience

AI product teams, operations leads, workflow owners, and technical evaluators.

## Capabilities

- Streamable HTTP MCP endpoint
- Bearer-token access for production calls
- Structured tool-call output
- Receipt-oriented evidence export
- Public server card and registry metadata
- MCP tool: register_agent_session
- MCP tool: read_workspace_roster
- MCP tool: write_handoff_note
- MCP tool: export_session_summary

## Public-Safe Boundary

This repository contains documentation only. It does not contain production source code, credentials, payment configuration, Cloudflare configuration, customer records, private analytics, or local machine paths.
