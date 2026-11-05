# Super.com

BoldCreate plugin that connects agents to Super.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Compare hotels and find the lowest rate.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Super.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Super.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install super-com@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "super-com": {
      "type": "http",
      "url": "https://www.super.com/travel/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Super.com: https://www.super.com/

## Logo

Neutral tile with the product's initials.}

## License

MIT
