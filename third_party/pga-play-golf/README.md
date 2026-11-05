# PGA – Play Golf

BoldCreate plugin that connects agents to PGA – Play Golf through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find a golf coach.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **PGA – Play Golf**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **PGA – Play Golf**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install pga-play-golf@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "pga-play-golf": {
      "type": "http",
      "url": "https://mcp.pga.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- PGA – Play Golf: https://www.pga.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
