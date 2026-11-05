# Craft.io

BoldCreate plugin that connects agents to Craft.io through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your end-to-end product lifecycle - backlog, PRDs, customer feedback, roadmaps, and strategic OKRs - with Claude connected directly to your Craft.io data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Craft.io**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Craft.io**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install craft-io@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "craft-io": {
      "type": "http",
      "url": "https://mcp.craft.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Craft.io in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Craft.io: https://craft.io/

## Logo

Icon downloaded from the Claude connector directory listing for Craft.io. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
