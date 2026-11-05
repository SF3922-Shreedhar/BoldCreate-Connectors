# Fiverr

BoldCreate plugin that connects agents to Fiverr through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find and hire freelancers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Fiverr**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Fiverr**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install fiverr-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "fiverr-mcp": {
      "type": "http",
      "url": "https://mcp.fiverr.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Fiverr: https://www.fiverr.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
