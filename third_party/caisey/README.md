# CAISey

BoldCreate plugin that connects agents to CAISey through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

CAISey gives CAIS platform users access to alternative investment products data made available on the platform.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **CAISey**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **CAISey**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install caisey@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "caisey": {
      "type": "http",
      "url": "https://mcp.caisgroup.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to CAISey in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- CAISey: https://www.caisgroup.com/

## Logo

Icon downloaded from the Claude connector directory listing for CAISey. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
