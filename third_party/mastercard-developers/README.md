# Mastercard Developers

BoldCreate plugin that connects agents to Mastercard Developers through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Up-to-date Mastercard APIs, docs, and guides.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Mastercard Developers**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Mastercard Developers**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mastercard-developers@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mastercard-developers": {
      "type": "http",
      "url": "https://developer.mcp.mastercard.com/"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Mastercard Developers: https://developer.mastercard.com/

## Logo

Neutral tile with the product's initials.

## License

MIT
