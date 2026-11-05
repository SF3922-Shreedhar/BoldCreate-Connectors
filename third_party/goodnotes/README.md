# Goodnotes

BoldCreate plugin that connects agents to Goodnotes through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Turn AI insights into documents.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Goodnotes**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Goodnotes**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install goodnotes@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "goodnotes": {
      "type": "http",
      "url": "https://claude-mcp-api.ml.goodnotes.com/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Goodnotes: https://goodnotes.com/

## Logo

Icon downloaded from the Claude connector directory listing for Goodnotes. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
