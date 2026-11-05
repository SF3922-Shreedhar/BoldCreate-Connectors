# Prophecy DataGPT

BoldCreate plugin that connects agents to Prophecy DataGPT through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Governed data work for business teams, right in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Prophecy DataGPT**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Prophecy DataGPT**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install datagpt-prophecy@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "datagpt-prophecy": {
      "type": "http",
      "url": "https://app.prophecy.ai/datagpt/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Prophecy DataGPT in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Prophecy DataGPT: https://www.prophecy.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
