# IP Author

BoldCreate plugin that connects agents to IP Author through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Patent search and analysis.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **IP Author**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **IP Author**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ip-author@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ip-author": {
      "type": "http",
      "url": "https://mcp.ipauthor.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to IP Author in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- IP Author: https://ipauthor.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
