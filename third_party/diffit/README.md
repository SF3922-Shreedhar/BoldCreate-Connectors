# Diffit

BoldCreate plugin that connects agents to Diffit through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Quality, classroom-ready resources for anything.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Diffit**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Diffit**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install diffit@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "diffit": {
      "type": "http",
      "url": "https://api.diffit.me/mcp/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Diffit in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Diffit: https://web.diffit.me/

## Logo

Icon downloaded from the Claude connector directory listing for Diffit. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
