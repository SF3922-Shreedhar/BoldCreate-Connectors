# Bitmovin

BoldCreate plugin that connects agents to Bitmovin through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Connect Bitmovin to access player, observability, encoding, ads and more in one place.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Bitmovin**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Bitmovin**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bitmovin@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bitmovin": {
      "type": "http",
      "url": "https://mcp.bitmovin.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Bitmovin in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Bitmovin: https://bitmovin.com/

## Logo

Icon downloaded from the Claude connector directory listing for Bitmovin. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
