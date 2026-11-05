# Zoho Show

BoldCreate plugin that connects agents to Zoho Show through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create, edit and manage presentation decks.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Zoho Show**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Zoho Show**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install zoho-show@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "zoho-show": {
      "type": "http",
      "url": "https://show.zoho.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Zoho Show in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Zoho Show: https://zoho.com/

## Logo

Icon downloaded from the Claude connector directory listing for Zoho Show. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
