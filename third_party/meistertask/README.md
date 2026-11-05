# MeisterTask

BoldCreate plugin that connects agents to MeisterTask through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create, search, and update tasks, projects, and notes.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MeisterTask**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MeisterTask**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install meistertask@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "meistertask": {
      "type": "http",
      "url": "https://mcp.meistertask.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MeisterTask in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MeisterTask: https://www.meisterlabs.com/

## Logo

Icon taken from the vendor's website (MeisterTask). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
