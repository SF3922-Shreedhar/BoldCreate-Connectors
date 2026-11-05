# Mollie

BoldCreate plugin that connects agents to Mollie through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Online and in-person payments, subscriptions, funding, reconciliation, and fraud prevention – so growth never means more providers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Mollie**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Mollie**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mollie@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mollie": {
      "type": "http",
      "url": "https://mcp.mollie.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Mollie in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Mollie: https://mollie.com/

## Logo

Icon taken from the vendor's website (Mollie). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
