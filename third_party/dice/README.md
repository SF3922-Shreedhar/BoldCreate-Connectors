# Dice

BoldCreate plugin that connects agents to Dice through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Find active tech jobs on Dice.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Dice**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Dice**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install dice@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "dice": {
      "type": "http",
      "url": "https://mcp.dice.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Dice: https://www.dice.com/

## Logo

Icon downloaded from the Claude connector directory listing for Dice. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
