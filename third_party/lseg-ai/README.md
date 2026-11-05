# LSEG AI

BoldCreate plugin that connects agents to LSEG AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Data Analytics and Trading.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **LSEG AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **LSEG AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lseg-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lseg-ai": {
      "type": "http",
      "url": "https://mcp.lseg.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to LSEG AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- LSEG AI: https://www.lseg.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
