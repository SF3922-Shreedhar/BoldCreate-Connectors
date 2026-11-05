# Meridian Connector for Xero

BoldCreate plugin that connects agents to Meridian Connector for Xero through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Make changes to Xero from within Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Meridian Connector for Xero**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Meridian Connector for Xero**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install meridian-connector-for-xer@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "meridian-connector-for-xer": {
      "type": "http",
      "url": "https://xero-connector.meridian.pilot.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Meridian Connector for Xero in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Meridian Connector for Xero: https://meridian.pilot.com/

## Logo

Icon downloaded from the Claude connector directory listing for Meridian Connector for Xero. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
