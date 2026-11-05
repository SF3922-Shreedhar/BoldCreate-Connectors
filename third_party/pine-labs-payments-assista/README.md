# Pine Labs Payments Assistant

BoldCreate plugin that connects agents to Pine Labs Payments Assistant through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query your Pine Labs payments data in plain language — orders, transactions, settlements, subscriptions and success rates, plus integration help for developers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Pine Labs Payments Assistant**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Pine Labs Payments Assistant**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pine-labs-payments-assista@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pine-labs-payments-assista": {
      "type": "http",
      "url": "https://mcp.pinelabs.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Pine Labs Payments Assistant in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Pine Labs Payments Assistant: https://www.pinelabs.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
