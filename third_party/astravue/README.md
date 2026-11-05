# Astravue App

BoldCreate plugin that connects agents to Astravue App through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage projects, tasks, and team workload in one place.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Astravue App**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Astravue App**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install astravue@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "astravue": {
      "type": "http",
      "url": "https://api.astravue.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Astravue App in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Astravue App: https://astravue.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
