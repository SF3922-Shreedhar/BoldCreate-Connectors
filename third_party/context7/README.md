# Context7

BoldCreate plugin that connects agents to Context7 through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Pull up-to-date, version-specific library docs and code examples into the prompt.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Context7**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Context7**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install context7@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "context7": {
      "type": "http",
      "url": "https://mcp.context7.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to their own account in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Context7 MCP server: https://context7.com/docs/resources/all-clients

## Logo

Icon downloaded from the Claude connector directory listing for Context7. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
