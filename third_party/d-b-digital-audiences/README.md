# D&B Digital Audiences

BoldCreate plugin that connects agents to D&B Digital Audiences through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Discover the Right Audiences Faster.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **D&B Digital Audiences**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **D&B Digital Audiences**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install d-b-digital-audiences@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "d-b-digital-audiences": {
      "type": "http",
      "url": "https://mcp.atportal.dnb.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to D&B Digital Audiences in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- D&B Digital Audiences: https://www.dnb.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
