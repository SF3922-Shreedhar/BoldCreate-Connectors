# Infobip Message

BoldCreate plugin that connects agents to Infobip Message through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Send SMS, RCS, MMS, and Viber messages through Infobip in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Infobip Message**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Infobip Message**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install infobip-message@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "infobip-message": {
      "type": "http",
      "url": "https://mcp.infobip.com/message"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Infobip Message in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Infobip Message: https://infobip.com/

## Logo

Icon downloaded from the Claude connector directory listing for Infobip Message. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
