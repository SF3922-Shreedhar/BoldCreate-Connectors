# Hanover Park

BoldCreate plugin that connects agents to Hanover Park through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your investment firm in real-time with access to portfolio, accounting, performance and LP data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Hanover Park**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Hanover Park**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install hanover-park@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "hanover-park": {
      "type": "http",
      "url": "https://app.hanoverpark.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Hanover Park in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Hanover Park: https://www.hanoverpark.com/

## Logo

Icon taken from the vendor's website (Hanover Park). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
