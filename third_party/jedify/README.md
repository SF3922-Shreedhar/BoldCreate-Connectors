# Jedify

BoldCreate plugin that connects agents to Jedify through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Governed, live business context for you and your agents - so they reason and act on your organization’s trusted data, definitions, and knowledge.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Jedify**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Jedify**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install jedify@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "jedify": {
      "type": "http",
      "url": "https://be.jedify.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Jedify in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Jedify: https://jedify.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
