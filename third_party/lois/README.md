# LOIS

BoldCreate plugin that connects agents to LOIS through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask questions about your Filevine matter documents and get answers grounded in them.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **LOIS**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **LOIS**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lois@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lois": {
      "type": "http",
      "url": "https://prod-us.lois-connector.filevine.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to LOIS in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- LOIS: https://filevine.com/

## Logo

Icon downloaded from the Claude connector directory listing for LOIS. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
