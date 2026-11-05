# isolved People Cloud

BoldCreate plugin that connects agents to isolved People Cloud through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your isolved data, inside Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **isolved People Cloud**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **isolved People Cloud**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install isolved@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "isolved": {
      "type": "http",
      "url": "https://api.myisolved.com/restmcp-prod/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to isolved People Cloud in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- isolved People Cloud: https://www.isolvedhcm.com/

## Logo

Icon downloaded from the Claude connector directory listing for isolved People Cloud. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
