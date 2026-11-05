# Macrobond Assist

BoldCreate plugin that connects agents to Macrobond Assist through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Spend your time on the analysis, not on finding the data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Macrobond Assist**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Macrobond Assist**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install macrobond-ai-datafeed-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "macrobond-ai-datafeed-mcp": {
      "type": "http",
      "url": "https://platform.macrobond.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Macrobond Assist in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Macrobond Assist: https://www.macrobond.com/

## Logo

Icon downloaded from the Claude connector directory listing for Macrobond Assist. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
