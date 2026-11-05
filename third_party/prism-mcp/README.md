# Revalidata Contracts

BoldCreate plugin that connects agents to Revalidata Contracts through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Revalidata – Contract Deadline Reader.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Revalidata Contracts**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Revalidata Contracts**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install prism-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "prism-mcp": {
      "type": "http",
      "url": "https://revalidata.com/api/prism-mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Revalidata Contracts in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Revalidata Contracts: https://builtai.co/

## Logo

Icon downloaded from the Claude connector directory listing for Revalidata Contracts. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
