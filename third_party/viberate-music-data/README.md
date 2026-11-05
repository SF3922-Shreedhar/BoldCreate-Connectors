# Viberate music data

BoldCreate plugin that connects agents to Viberate music data through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Music industry data inside Claude — artists, tracks, festivals, charts.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Viberate music data**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Viberate music data**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install viberate-music-data@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "viberate-music-data": {
      "type": "http",
      "url": "https://mcp.viberate.com/v1/sse"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Viberate music data in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Viberate music data: https://viberate.com/

## Logo

Icon taken from the vendor's website (Viberate music data). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
