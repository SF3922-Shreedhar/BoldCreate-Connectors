# Eedi

BoldCreate plugin that connects agents to Eedi through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Access Eedi's high quality math questions.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Eedi**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Eedi**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install eedi@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "eedi": {
      "type": "http",
      "url": "https://teacher-tools.eedi.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Eedi in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Eedi: https://www.eedi.com/

## Logo

Icon downloaded from the Claude connector directory listing for Eedi. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
