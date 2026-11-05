# Mary

BoldCreate plugin that connects agents to Mary through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Organise, extract, draft, and verify the facts of your matter.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Mary**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Mary**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mary@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mary": {
      "type": "http",
      "url": "https://mcp.us.marytechnology.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Mary in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Mary: https://marytechnology.com/

## Logo

Icon downloaded from the Claude connector directory listing for Mary. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
