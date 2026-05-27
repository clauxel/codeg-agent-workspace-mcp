# Quickstart

CodeG Agent Workspace is a hosted remote MCP for CodeG.

## Fast Path

1. Open CodeG Agent Workspace and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://codegworkspace.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call register_agent_session with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://codegworkspace.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=quickstart_home
- https://codegworkspace.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=quickstart_pricing
- https://codegworkspace.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=codegworkspace_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://codegworkspace.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
