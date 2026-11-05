# Chaser

BoldCreate plugin that connects agents to Chaser through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Task management and project tracking inside Slack.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Chaser**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Chaser**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install chaser@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "chaser": {
      "type": "http",
      "url": "https://api.trychaser.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Chaser in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Chaser: https://www.trychaser.com/

## Logo

Icon taken from the vendor's website (Chaser). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
