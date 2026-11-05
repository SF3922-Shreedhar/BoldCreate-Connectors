# Infobip Documentation

BoldCreate plugin that connects agents to Infobip Documentation through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search and browse Infobip docs from Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Infobip Documentation**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Infobip Documentation**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install infobip-documentation@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "infobip-documentation": {
      "type": "http",
      "url": "https://mcp.infobip.com/search"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Infobip Documentation: https://infobip.com/

## Logo

Icon downloaded from the Claude connector directory listing for Infobip Documentation. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
