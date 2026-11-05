# Privacy.com

BoldCreate plugin that connects agents to Privacy.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage virtual cards and track your spending patterns.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Privacy.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Privacy.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install privacy@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "privacy": {
      "type": "http",
      "url": "https://mcp.privacy.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Privacy.com in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Privacy.com: https://privacy.com/

## Logo

Icon downloaded from the Claude connector directory listing for Privacy.com. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
