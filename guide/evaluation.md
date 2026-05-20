# Evaluation Guide

Use this page to evaluate whether A2A Dependency Inspector fits a real workflow.

## What To Test

- A2A dependency inspector MCP
- A2A Dependency Inspector
- A2A Dependency Inspector documentation
- A2A Dependency Inspector remote MCP
- a2adependencyinspector server card

## Expected Evidence

- Open A2A Dependency Inspector and select the buyer plan.
- Create or request a bearer token from the hosted product.
- Add https://a2adependencyinspector.clauxel.com/mcp to a compatible MCP client.
- Run tools/list, then call inspect_a2a_dependencies with public-safe sample data.
- Save the returned receipt or export for human review.

## Risk Checks

- Do not put API keys, tokens, payment details, private logs, or customer records in public issues.
- Use public-safe sample data for examples and directory submissions.
- Treat generated receipts and scores as reviewer evidence, not as a substitute for accountable human approval.
- Validate release or migration gates against a staging workflow before production rollout.

## Buyer Path

Default plan: team.

- https://a2adependencyinspector.clauxel.com/checkout/?utm_source=github&utm_medium=documentation&utm_campaign=a2adependencyinspector_public_docs&utm_content=evaluation_checkout
