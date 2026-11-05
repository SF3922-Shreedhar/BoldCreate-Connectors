# Loopio

BoldCreate plugin that connects agents to Loopio through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search approved response content, answer entire RFPs, and manage projects effortlessly.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Loopio**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Loopio**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install loopio@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "loopio": {
      "type": "http",
      "url": "https://mcp-server.loopio.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Loopio in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Loopio: https://loopio.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
