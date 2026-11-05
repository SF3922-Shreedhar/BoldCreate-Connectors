# Tixel

BoldCreate plugin that connects agents to Tixel through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Buy and sell tickets safely, fan to fan, at fair prices.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tixel**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tixel**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tixel@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tixel": {
      "type": "http",
      "url": "https://mcp-v1.tixel.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Tixel: https://tixel.com/

## Logo

Icon downloaded from the Claude connector directory listing for Tixel. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
