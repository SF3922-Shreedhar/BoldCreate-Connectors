# Ample Computer

BoldCreate plugin that connects agents to Ample Computer through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Deploy apps, databases and storage from Claude and get a live URL, with no servers or cloud console to set up.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ample Computer**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ample Computer**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ample-computer@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ample-computer": {
      "type": "http",
      "url": "https://api.ample.computer/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ample Computer in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Ample Computer: https://ample.computer/

## Logo

Neutral tile with the product's initials.

## License

MIT
