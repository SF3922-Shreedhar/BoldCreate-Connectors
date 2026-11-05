# MindMeister

BoldCreate plugin that connects agents to MindMeister through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Build, search, and edit mind maps in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MindMeister**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MindMeister**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mindmeister@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mindmeister": {
      "type": "http",
      "url": "https://mcp.mindmeister.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MindMeister in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MindMeister: https://www.meisterlabs.com/

## Logo

Icon taken from the vendor's website (MindMeister). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
