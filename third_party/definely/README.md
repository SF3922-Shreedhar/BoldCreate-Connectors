# Definely

BoldCreate plugin that connects agents to Definely through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Structured contract review tools for legal teams.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Definely**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Definely**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install definely@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "definely": {
      "type": "http",
      "url": "https://mcp.app.definely.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Definely in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Definely: https://www.definely.com/

## Logo

Icon downloaded from the Claude connector directory listing for Definely. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
