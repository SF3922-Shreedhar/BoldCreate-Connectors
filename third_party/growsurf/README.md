# GrowSurf

BoldCreate plugin that connects agents to GrowSurf through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build and manage GrowSurf referral and affiliate programs with Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **GrowSurf**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **GrowSurf**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install growsurf@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "growsurf": {
      "type": "http",
      "url": "https://mcp.growsurf.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to GrowSurf in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- GrowSurf: https://growsurf.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
