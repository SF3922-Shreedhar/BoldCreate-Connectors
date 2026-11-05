# Light

BoldCreate plugin that connects agents to Light through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Work with your Light finance data in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Light**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Light**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install light@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "light": {
      "type": "http",
      "url": "https://api.light.inc/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Light in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Light: https://www.light.inc/

## Logo

Icon downloaded from the Claude connector directory listing for Light. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
