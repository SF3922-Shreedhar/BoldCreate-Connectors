# Unify

BoldCreate plugin that connects agents to Unify through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find, enrich, and sequence prospects from 40+ data sources.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Unify**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Unify**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install unify@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "unify": {
      "type": "http",
      "url": "https://mcp.unifygtm.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Unify in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Unify: https://www.unifygtm.com/

## Logo

Icon downloaded from the Claude connector directory listing for Unify. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
