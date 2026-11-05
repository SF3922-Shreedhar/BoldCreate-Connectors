# Find Your Great

BoldCreate plugin that connects agents to Find Your Great through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Understand your work impact — ask about what you actually did, decided, and changed.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Find Your Great**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Find Your Great**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install find-your-great@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "find-your-great": {
      "type": "http",
      "url": "https://findyourgreat.com/mcp/v1"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Find Your Great in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Find Your Great: https://findyourgreat.com/

## Logo

Icon downloaded from the Claude connector directory listing for Find Your Great. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
