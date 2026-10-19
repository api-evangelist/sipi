---
name: evaluate-spend
description: Evaluate whether a spend is approved, blocked, or flagged.
api: https://sipi.bot/api/mcp
operations:
  - evaluateTransaction
---

## Steps
1. Call the `evaluate_spend` tool (MCP) which maps to the OpenAPI operation `evaluateTransaction`.
2. Provide transaction details as per the OpenAPI schema.
3. Receive decision `APPROVED`, `BLOCKED`, or `FLAGGED`.
