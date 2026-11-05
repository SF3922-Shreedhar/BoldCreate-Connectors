# Lorikeet

BoldCreate plugin that connects agents to Lorikeet through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

A universal concierge for complex businesses.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Lorikeet**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Lorikeet**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lorikeet@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lorikeet": {
      "type": "http",
      "url": "https://mcp.lorikeetcx.ai/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Lorikeet in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Lorikeet: https://www.lorikeetcx.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Lorikeet. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
