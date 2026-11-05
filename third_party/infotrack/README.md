# InfoTrack

BoldCreate plugin that connects agents to InfoTrack through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Australian legal, property and compliance searches.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **InfoTrack**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **InfoTrack**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install infotrack@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "infotrack": {
      "type": "http",
      "url": "https://mcp.infotrack.ai/servers/infotrack-all/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to InfoTrack in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- InfoTrack: https://www.infotrack.ai/

## Logo

Icon downloaded from the Claude connector directory listing for InfoTrack. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
