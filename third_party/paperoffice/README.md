# PaperOffice

BoldCreate plugin that connects agents to PaperOffice through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Built for companies. Ready for AI agents. The headless DMS for Claude: search, read, extract, approve, send for signing and archive documents in your own account, with your permissions.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **PaperOffice**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **PaperOffice**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install paperoffice@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "paperoffice": {
      "type": "http",
      "url": "https://mcp.paperoffice.ai/claude"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to PaperOffice in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- PaperOffice: https://paperoffice.ai/

## Logo

Icon taken from the vendor's website (PaperOffice). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
