# LinkSquares

BoldCreate plugin that connects agents to LinkSquares through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Automate legal intake and contract intelligence — create agreements, manage legal requests, and search your contract data directly from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **LinkSquares**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **LinkSquares**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install linksquares@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "linksquares": {
      "type": "http",
      "url": "https://ai-chat-service.linksquares.com/v1/mcp/external"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to LinkSquares in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- LinkSquares: https://linksquares.com/

## Logo

Icon downloaded from the Claude connector directory listing for LinkSquares. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
