# DataCamp

BoldCreate plugin that connects agents to DataCamp through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

DataCamp catalog and team admin for your AI assistant.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **DataCamp**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **DataCamp**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install datacamp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "datacamp": {
      "type": "http",
      "url": "https://mcp.datacamp.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- DataCamp: https://www.datacamp.com/

## Logo

Icon downloaded from the Claude connector directory listing for DataCamp. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
