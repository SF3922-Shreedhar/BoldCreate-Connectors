# Spacefast

BoldCreate plugin that connects agents to Spacefast through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build and share your AI work.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Spacefast**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Spacefast**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install spacefast@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "spacefast": {
      "type": "http",
      "url": "https://mcp.spacefast.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Spacefast in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Spacefast: https://spacefast.com/

## Logo

Icon downloaded from the Claude connector directory listing for Spacefast. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
