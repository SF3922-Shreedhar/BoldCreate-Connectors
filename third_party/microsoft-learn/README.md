# Microsoft Learn

BoldCreate plugin that connects agents to Microsoft Learn through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search official Microsoft docs and code samples for .NET, Azure, MAUI, and more.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Microsoft Learn**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Microsoft Learn**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install microsoft-learn@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "microsoft-learn": {
      "type": "http",
      "url": "https://learn.microsoft.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

This server needs no account or key.

## Docs

- Microsoft Learn MCP server: https://learn.microsoft.com/training/support/mcp

## Logo

Icon taken from the vendor's website (Microsoft Learn). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
