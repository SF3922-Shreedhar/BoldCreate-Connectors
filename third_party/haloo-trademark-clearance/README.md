# Haloo Trademark Clearance

BoldCreate plugin that connects agents to Haloo Trademark Clearance through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Full trademark clearance search, direct in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Haloo Trademark Clearance**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Haloo Trademark Clearance**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install haloo-trademark-clearance@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "haloo-trademark-clearance": {
      "type": "http",
      "url": "https://connect.haloo.ai/trademark-search/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Haloo Trademark Clearance in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Haloo Trademark Clearance: https://haloo.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
