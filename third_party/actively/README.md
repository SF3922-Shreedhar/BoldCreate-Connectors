# Actively

BoldCreate plugin that connects agents to Actively through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

1:1 account agents for GTM teams.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Actively**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Actively**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install actively@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "actively": {
      "type": "http",
      "url": "https://api.actively.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Actively in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Actively: https://www.actively.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Actively. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
