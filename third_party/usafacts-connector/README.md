# USAFacts Government Data Connector

BoldCreate plugin that connects agents to USAFacts Government Data Connector through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Give Claude a better source for government data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **USAFacts Government Data Connector**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **USAFacts Government Data Connector**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install usafacts-connector@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "usafacts-connector": {
      "type": "http",
      "url": "https://data.mcp.usafacts.org/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- USAFacts Government Data Connector: https://usafacts.org/

## Logo

Icon taken from the vendor's website (USAFacts Government Data Connector). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
