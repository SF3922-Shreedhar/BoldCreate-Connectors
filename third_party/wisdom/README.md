# WisdomAI

BoldCreate plugin that connects agents to WisdomAI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Trustworthy answers from your governed enterprise data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **WisdomAI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **WisdomAI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install wisdom@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "wisdom": {
      "type": "http",
      "url": "https://mcp.wisdom.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to WisdomAI in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- WisdomAI: https://www.wisdom.ai/

## Logo

Icon downloaded from the Claude connector directory listing for WisdomAI. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
