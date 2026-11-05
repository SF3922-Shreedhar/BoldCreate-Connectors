# Attentive

BoldCreate plugin that connects agents to Attentive through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Attentive, inside the AI tools you already use.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Attentive**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Attentive**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install attentive@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "attentive": {
      "type": "http",
      "url": "https://attentive-ui-mcp.attentivemobile.com/mcp?readOnly=false"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Attentive in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Attentive: https://www.attentive.com/

## Logo

Icon downloaded from the Claude connector directory listing for Attentive. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
