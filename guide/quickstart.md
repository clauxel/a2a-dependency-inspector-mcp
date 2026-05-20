# Quickstart

A2A Dependency Inspector is a hosted remote MCP for A2A dependency inspector MCP.

## Fast Path

1. Open A2A Dependency Inspector and select the buyer plan.
2. Create or request a bearer token from the hosted product.
3. Add https://a2adependencyinspector.clauxel.com/mcp to a compatible MCP client.
4. Run tools/list, then call inspect_a2a_dependencies with public-safe sample data.
5. Save the returned receipt or export for human review.

## Useful Links

- https://a2adependencyinspector.clauxel.com/?utm_source=github&utm_medium=documentation&utm_campaign=a2adependencyinspector_public_docs&utm_content=quickstart_home
- https://a2adependencyinspector.clauxel.com/pricing/?utm_source=github&utm_medium=documentation&utm_campaign=a2adependencyinspector_public_docs&utm_content=quickstart_pricing
- https://a2adependencyinspector.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2adependencyinspector_public_docs&utm_content=quickstart_checkout

## MCP Endpoint

```text
https://a2adependencyinspector.clauxel.com/mcp
```

Use bearer-token authentication for production calls. Keep the token in the MCP client's secret mechanism.
