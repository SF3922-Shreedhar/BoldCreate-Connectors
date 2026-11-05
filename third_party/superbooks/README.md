# SuperBooks

BoldCreate plugin that connects agents to SuperBooks through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Financial OS for small businesses.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **SuperBooks**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **SuperBooks**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install superbooks@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "superbooks": {
      "type": "http",
      "url": "https://app.superbooks.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to SuperBooks in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- SuperBooks: https://devino.ca/

## Logo

Icon downloaded from the Claude connector directory listing for SuperBooks. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
