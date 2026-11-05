# bolna

BoldCreate plugin that connects agents to bolna through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage Bolna voice AI agents and review call history and transcripts from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **bolna**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **bolna**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bolna@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bolna": {
      "type": "http",
      "url": "https://mcp.bolna.ai/api/connector/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to bolna in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- bolna: https://bolna.ai/

## Logo

Icon taken from the vendor's website (bolna). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
