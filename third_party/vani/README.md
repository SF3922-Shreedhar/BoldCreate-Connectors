# Vani by Zoho

BoldCreate plugin that connects agents to Vani by Zoho through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create diagrams, visualize workflows, and manage Spaces in Vani.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Vani by Zoho**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Vani by Zoho**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vani@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vani": {
      "type": "http",
      "url": "https://app.vanihq.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Vani by Zoho in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Vani by Zoho: https://zoho.com/

## Logo

Icon downloaded from the Claude connector directory listing for Vani by Zoho. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
