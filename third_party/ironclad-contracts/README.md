# Ironclad Contracts

BoldCreate plugin that connects agents to Ironclad Contracts through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Plain language search for faster contract answers and manage your contractual obligations.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ironclad Contracts**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ironclad Contracts**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ironclad-contracts@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ironclad-contracts": {
      "type": "http",
      "url": "https://mcp.na1.ironcladapp.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ironclad Contracts in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Ironclad Contracts: https://ironcladapp.com/

## Logo

Icon downloaded from the Claude connector directory listing for Ironclad Contracts. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
