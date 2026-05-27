# Evaluation Guide

Use this page to evaluate whether CodeG Agent Workspace fits a real workflow.

## What To Test

- CodeG
- CodeG Agent Workspace
- CodeG Agent Workspace documentation
- CodeG Agent Workspace remote MCP
- codegworkspace server card

## Expected Evidence

- Open CodeG Agent Workspace and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://codegworkspace.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call register_agent_session with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.

## Buyer Path

Default plan: team.

- https://codegworkspace.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=evaluation_checkout
