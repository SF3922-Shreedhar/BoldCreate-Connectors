# OnChainDiligence

BoldCreate plugin that connects agents to OnChainDiligence through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Inspect autonomous payments before execution and independently verify evidence afterward.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **OnChainDiligence**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **OnChainDiligence**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install onchaindiligence@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "onchaindiligence": {
      "type": "http",
      "url": "https://mcp.onchaindiligence.com/public/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- OnChainDiligence: https://onchaindiligence.com/

## Logo

Icon downloaded from the Claude connector directory listing for OnChainDiligence. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
