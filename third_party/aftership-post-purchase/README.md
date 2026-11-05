# AfterShip Post-Purchase

BoldCreate plugin that connects agents to AfterShip Post-Purchase through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Track shipments and returns with AfterShip context.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **AfterShip Post-Purchase**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **AfterShip Post-Purchase**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install aftership-post-purchase@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "aftership-post-purchase": {
      "type": "http",
      "url": "https://mcp.aftership.com/post-purchase"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to AfterShip Post-Purchase in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- AfterShip Post-Purchase: https://www.aftership.com/ (vendor homepage; the sandbox could not load it, so the link is not verified)

## Logo

Icon downloaded from the Claude connector directory listing for AfterShip Post-Purchase. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
