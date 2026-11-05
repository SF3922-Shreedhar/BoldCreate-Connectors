# Fax.Plus

BoldCreate plugin that connects agents to Fax.Plus through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Send and receive faxes securely from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Fax.Plus**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Fax.Plus**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install fax-plus@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "fax-plus": {
      "type": "http",
      "url": "https://mcp.fax.plus/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Fax.Plus in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Fax.Plus: https://www.alohi.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
