# MYOB

BoldCreate plugin that connects agents to MYOB through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Understand your MYOB business finances with Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MYOB**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MYOB**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install myob@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "myob": {
      "type": "http",
      "url": "https://mcp.myob.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MYOB in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MYOB: https://www.myob.com/

## Logo

Icon downloaded from the Claude connector directory listing for MYOB. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
