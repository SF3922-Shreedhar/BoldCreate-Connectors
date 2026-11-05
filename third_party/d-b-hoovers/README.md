# D&B Hoovers

BoldCreate plugin that connects agents to D&B Hoovers through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Access trusted D&B intelligence, contacts, and signals to uncover opportunities and take the next best action.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **D&B Hoovers**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **D&B Hoovers**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install d-b-hoovers@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "d-b-hoovers": {
      "type": "http",
      "url": "https://mcp.hoovers.dnb.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to D&B Hoovers in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- D&B Hoovers: https://www.dnb.com/

## Logo

Icon taken from the vendor's website (D&B Hoovers). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
