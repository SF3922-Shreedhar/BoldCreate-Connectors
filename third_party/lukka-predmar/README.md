# Lukka Prediction Markets Data MCP

BoldCreate plugin that connects agents to Lukka Prediction Markets Data MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Prediction market intelligence across several venues, including Kalshi and Polymarket: market discovery, classification, pricing, open interest and volume.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Lukka Prediction Markets Data MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Lukka Prediction Markets Data MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lukka-predmar@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lukka-predmar": {
      "type": "http",
      "url": "https://predmar.mcp.lukka.tech/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Lukka Prediction Markets Data MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Lukka Prediction Markets Data MCP: https://lukka.tech/

## Logo

Neutral tile with the product's initials.

## License

MIT
