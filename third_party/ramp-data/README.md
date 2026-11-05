# Ramp Data

BoldCreate plugin that connects agents to Ramp Data through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search and analyze Ramp spend across 50,000+ businesses.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ramp Data**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ramp Data**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ramp-data@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ramp-data": {
      "type": "http",
      "url": "https://mcp.ramp.com/ramp-data/anthropic/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Ramp Data: https://ramp.com/

## Logo

Icon taken from the vendor's website (Ramp Data), because the Claude connector directory links to a web page instead of an image file. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
