# Hubstaff

BoldCreate plugin that connects agents to Hubstaff through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-ready workforce insights.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Hubstaff**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Hubstaff**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install hubstaff@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "hubstaff": {
      "type": "http",
      "url": "https://mcp.hubstaff.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Hubstaff in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Hubstaff: https://hubstaff.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
