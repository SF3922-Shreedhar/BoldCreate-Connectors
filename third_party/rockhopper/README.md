# Rockhopper

BoldCreate plugin that connects agents to Rockhopper through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

The audit trail and governance layer for every file your team and your AI touch.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Rockhopper**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Rockhopper**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install rockhopper@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "rockhopper": {
      "type": "http",
      "url": "https://mcp.rockhopper.co/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Rockhopper in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Rockhopper: https://www.rockhopper.co/

## Logo

Icon taken from the vendor's website (Rockhopper). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
