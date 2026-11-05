# Meridian AI

BoldCreate plugin that connects agents to Meridian AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query your deals, companies, documents, and more.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Meridian AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Meridian AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install meridian-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "meridian-ai": {
      "type": "http",
      "url": "https://mcp.meridian-ai.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Meridian AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Meridian AI: https://www.meridian-ai.com/

## Logo

Icon downloaded from the Claude connector directory listing for Meridian AI. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
