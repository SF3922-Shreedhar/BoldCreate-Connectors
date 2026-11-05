# LawY

BoldCreate plugin that connects agents to LawY through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Efficiently work with your legal matters and documents from within Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **LawY**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **LawY**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install lawy@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "lawy": {
      "type": "http",
      "url": "https://mcp.connected-agents.lawy.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to LawY in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- LawY: https://www.lawy.ai/

## Logo

Icon taken from the vendor's website (LawY). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
