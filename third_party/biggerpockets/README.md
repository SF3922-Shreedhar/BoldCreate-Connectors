# BiggerPockets

BoldCreate plugin that connects agents to BiggerPockets through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Underwrite real estate deals and search BiggerPockets' investing library.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **BiggerPockets**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **BiggerPockets**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install biggerpockets@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "biggerpockets": {
      "type": "http",
      "url": "https://www.biggerpockets.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to BiggerPockets in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- BiggerPockets: https://www.biggerpockets.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
