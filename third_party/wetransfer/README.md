# WeTransfer

BoldCreate plugin that connects agents to WeTransfer through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Send files from your chat via WeTransfer — get a shareable link or email them to recipients, using your own WeTransfer account.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **WeTransfer**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **WeTransfer**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install wetransfer@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "wetransfer": {
      "type": "http",
      "url": "https://mcp-server.wetransfer.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to WeTransfer in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- WeTransfer: https://wetransfer.com/

## Logo

Icon taken from the vendor's website (WeTransfer). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
