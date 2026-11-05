# viaNexus vAST

BoldCreate plugin that connects agents to viaNexus vAST through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Power AI workflows with viaNexus: a financial data marketplace delivering prices, news, fundamentals, and global macro economic data directly from trusted provider partners.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **viaNexus vAST**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **viaNexus vAST**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install vianexus-vast@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "vianexus-vast": {
      "type": "http",
      "url": "https://vast.blueskyapi.com/vianexus/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to viaNexus vAST in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- viaNexus vAST: https://vianexus.com/

## Logo

Icon downloaded from the Claude connector directory listing for viaNexus vAST. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
