# Bitrise MCP

BoldCreate plugin that connects agents to Bitrise MCP through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Set up and manage mobile CI/CD on Bitrise: build, test, and distribute iOS, Android, Flutter, and React Native apps from your AI assistant.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Bitrise MCP**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Bitrise MCP**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bitrise-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bitrise-mcp": {
      "type": "http",
      "url": "https://mcp.bitrise.io/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Bitrise MCP in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Bitrise MCP: https://bitrise.io/

## Logo

Icon downloaded from the Claude connector directory listing for Bitrise MCP. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
