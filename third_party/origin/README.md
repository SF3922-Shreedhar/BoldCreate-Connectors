# Origin

BoldCreate plugin that connects agents to Origin through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

See what AI agents are doing across your endpoint fleet.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Origin**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Origin**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install origin@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "origin": {
      "type": "http",
      "url": "https://mcp.prod.originhq.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Origin in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Origin: https://www.originhq.com/

## Logo

Icon downloaded from the Claude connector directory listing for Origin. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
