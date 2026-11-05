# Addgene

BoldCreate plugin that connects agents to Addgene through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search Addgene's catalog of plasmids and viral preps.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Addgene**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Addgene**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install addgene@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "addgene": {
      "type": "http",
      "url": "https://mcp-server.addgene.org/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Addgene in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Addgene: https://www.addgene.org/

## Logo

Neutral tile with the product's initials.

## License

MIT
