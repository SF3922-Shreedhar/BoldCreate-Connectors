# Jump

BoldCreate plugin that connects agents to Jump through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Trusted AI for advisors & financial professionals.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Jump**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Jump**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install jump-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "jump-mcp": {
      "type": "http",
      "url": "https://my.jumpapp.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Jump in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Jump: https://jump.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Jump. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
