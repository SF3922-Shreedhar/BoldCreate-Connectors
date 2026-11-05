# stub

BoldCreate plugin that connects agents to stub through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Super simple AI native accounting.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **stub**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **stub**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install stub@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "stub": {
      "type": "http",
      "url": "https://api.stub.africa/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to stub in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- stub: https://stub.africa/

## Logo

Icon taken from the vendor's website (stub). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
