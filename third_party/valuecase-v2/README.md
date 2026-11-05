# Valuecase App

BoldCreate plugin that connects agents to Valuecase App through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, create and update Valuecase spaces.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Valuecase App**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Valuecase App**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install valuecase-v2@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "valuecase-v2": {
      "type": "http",
      "url": "https://mcp.valuecase.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Valuecase App in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Valuecase App: https://valuecase.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
