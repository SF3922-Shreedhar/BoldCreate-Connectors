# Zacks Data

BoldCreate plugin that connects agents to Zacks Data through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Trusted Financial Data from Zacks Investment Research.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Zacks Data**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Zacks Data**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install zacks-data@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "zacks-data": {
      "type": "http",
      "url": "https://mcp.zacksdata.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Zacks Data in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Zacks Data: https://ai.zacksdata.com/

## Logo

Icon downloaded from the Claude connector directory listing for Zacks Data. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
