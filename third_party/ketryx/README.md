# Ketryx

BoldCreate plugin that connects agents to Ketryx through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search and explore regulated software lifecycle data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ketryx**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ketryx**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ketryx@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ketryx": {
      "type": "http",
      "url": "https://app.ketryx.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ketryx in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Ketryx: https://www.ketryx.com/

## Logo

Icon downloaded from the Claude connector directory listing for Ketryx. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
