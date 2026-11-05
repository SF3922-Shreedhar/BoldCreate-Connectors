# Agility CMS

BoldCreate plugin that connects agents to Agility CMS through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI pipelines for developers and marketers. Model content, author pages, publish updates, and manage media across multiple Agility CMS instances through natural language.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Agility CMS**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Agility CMS**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install agility-cms@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "agility-cms": {
      "type": "http",
      "url": "https://mcp.agilitycms.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Agility CMS in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Agility CMS: https://agilitycms.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
