# DualEntry

BoldCreate plugin that connects agents to DualEntry through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, create, and manage your DualEntry accounting data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **DualEntry**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **DualEntry**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install dualentry@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "dualentry": {
      "type": "http",
      "url": "https://api.dualentry.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to DualEntry in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- DualEntry: https://dualentry.com/

## Logo

Icon downloaded from the Claude connector directory listing for DualEntry. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
