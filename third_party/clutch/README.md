# Clutch.co

BoldCreate plugin that connects agents to Clutch.co through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find the perfect B2B company with verified client reviews.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Clutch.co**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Clutch.co**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install clutch@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "clutch": {
      "type": "http",
      "url": "https://bot.clutch.co/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Clutch.co: https://clutch.co/

## Logo

Icon downloaded from the Claude connector directory listing for Clutch.co. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
