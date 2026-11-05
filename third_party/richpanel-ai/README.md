# Richpanel AI

BoldCreate plugin that connects agents to Richpanel AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your Richpanel helpdesk and AI support agent from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Richpanel AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Richpanel AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install richpanel-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "richpanel-ai": {
      "type": "http",
      "url": "https://mcp.richpanel.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Richpanel AI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Richpanel AI: https://richpanel.com/

## Logo

Icon taken from the vendor's website (Richpanel AI). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
