# Toffu

BoldCreate plugin that connects agents to Toffu through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your AI marketing teammate — pulls analytics and runs ad campaigns across Google, Meta, LinkedIn, and more.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Toffu**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Toffu**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install toffu@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "toffu": {
      "type": "http",
      "url": "https://mcp.toffu.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Toffu in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Toffu: https://toffu.ai/

## Logo

Icon taken from the vendor's website (Toffu). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
