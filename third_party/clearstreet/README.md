# Clear Street

BoldCreate plugin that connects agents to Clear Street through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Research and Analyze Stocks and Options.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Clear Street**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Clear Street**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install clearstreet@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "clearstreet": {
      "type": "http",
      "url": "https://api.clearstreet.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Clear Street in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Clear Street: https://www.clearstreet.com/

## Logo

Icon taken from the vendor's website (Clear Street). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
