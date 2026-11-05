# Savri

BoldCreate plugin that connects agents to Savri through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Privacy-friendly web analytics, ask in plain English.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Savri**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Savri**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install savri@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "savri": {
      "type": "http",
      "url": "https://savri.io/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Savri in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Savri: https://savri.io/

## Logo

Icon downloaded from the Claude connector directory listing for Savri. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
