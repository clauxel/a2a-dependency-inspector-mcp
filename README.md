# A2A Dependency Inspector MCP

A2A dependency inspector MCP with structured receipts.

Paid remote MCP for A2A dependency inspector MCP, structured receipts, audit logs, and reviewer-ready evidence.

## Public Endpoints

- Website: https://a2adependencyinspector.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- MCP endpoint: https://a2adependencyinspector.clauxel.com/mcp
- Server card: https://a2adependencyinspector.clauxel.com/server-card.json
- Registry name: `com.clauxel.a2adependencyinspector/a2adependencyinspector-mcp`

## Access

This is a paid hosted remote MCP. Production calls require a bearer token issued from the product website.

```http
Authorization: Bearer <token>
```

Unauthenticated browser visits to `/mcp` return a clear JSON error instead of internal details.

## Tools

- `inspect_a2a_dependencies`
- `extract_message_edges`
- `detect_dependency_cycles`
- `issue_rollout_receipt`
- `export_dependency_log`

## Quick Start

1. Open the website and choose a plan.
2. Create or request an API token.
3. Add the endpoint to an MCP client that supports Streamable HTTP remote servers.
4. Send JSON-RPC requests with the bearer token.

## Useful Links

- Product page: https://a2adependencyinspector.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605
- Pricing: https://a2adependencyinspector.clauxel.com/?utm_source=github&utm_medium=directory&utm_campaign=sbl202605#pricing
- Server card: https://a2adependencyinspector.clauxel.com/server-card.json
- MCP endpoint: https://a2adependencyinspector.clauxel.com/mcp

## Status

This repository is a public documentation and directory-submission reference for the hosted service. It does not contain the private production source code.
