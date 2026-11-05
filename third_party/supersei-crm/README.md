# Supersei CRM

BoldCreate plugin that connects agents to Supersei CRM through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your Supersei sales CRM from a conversation: leads, calls, WhatsApp, meetings, campaigns, reports and workspace setup, with exactly your permissions.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Supersei CRM**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Supersei CRM**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install supersei-crm@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "supersei-crm": {
      "type": "http",
      "url": "https://api.supersei.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Supersei CRM in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Supersei CRM: https://supersei.ai/

## Logo

Icon taken from the vendor's website (Supersei CRM). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
