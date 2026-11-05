# Orion

BoldCreate plugin that connects agents to Orion through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring Orion Connect portfolio data and Redtail CRM together in Claude — prep for client meetings, capture follow-ups, prioritize your pipeline, and turn reports into talking points.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Orion**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Orion**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install orion-advisor-solutions@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "orion-advisor-solutions": {
      "type": "http",
      "url": "https://gateway.oriondenali.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Orion in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Orion: https://orion.com/

## Logo

Icon downloaded from the Claude connector directory listing for Orion. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
