# Chariot

BoldCreate plugin that connects agents to Chariot through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Manage your nonprofit's DAF donations and deposits.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Chariot**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Chariot**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install chariot@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "chariot": {
      "type": "http",
      "url": "https://api.givechariot.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Chariot in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Chariot: https://givechariot.com/

## Logo

Icon taken from the vendor's website (Chariot). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
