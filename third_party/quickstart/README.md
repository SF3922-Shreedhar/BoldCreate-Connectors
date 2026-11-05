# QuickStart

BoldCreate plugin that connects agents to QuickStart through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

AI-powered accounting.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **QuickStart**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **QuickStart**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install quickstart@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "quickstart": {
      "type": "http",
      "url": "https://my.quickstartapi.netsuite.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to QuickStart in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- QuickStart: https://www.netsuite.com/quickstart.shtml (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Icon downloaded from the Claude connector directory listing for QuickStart. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
