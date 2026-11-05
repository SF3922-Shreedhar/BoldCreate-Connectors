# Migma

BoldCreate plugin that connects agents to Migma through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Run your entire email marketing from Claude. Migma designs on-brand campaigns, sends when you approve, and gets better with every send.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Migma**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Migma**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install migma@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "migma": {
      "type": "http",
      "url": "https://migma.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Migma in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Migma: https://migma.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Migma. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
