# Clio

BoldCreate plugin that connects agents to Clio through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Research the law, analyze dockets and develop case strategy with Clio Library and Clio Docket, with citations back to the sources.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Clio**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Clio**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install clio@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "clio": {
      "type": "http",
      "url": "https://mcp.api.clio.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Clio in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Clio: https://www.clio.com/

## Logo

Icon downloaded from the Claude connector directory listing for Clio. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
