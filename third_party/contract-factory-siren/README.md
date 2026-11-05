# Contract-Factory — Sociétés & SIREN

BoldCreate plugin that connects agents to Contract-Factory — Sociétés & SIREN through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Infos officielles des entreprises françaises (RNE).

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Contract-Factory — Sociétés & SIREN**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Contract-Factory — Sociétés & SIREN**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install contract-factory-siren@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "contract-factory-siren": {
      "type": "http",
      "url": "https://www.contract-factory.com/mcp.php"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Contract-Factory — Sociétés & SIREN: https://www.contract-factory.com/

## Logo

Icon downloaded from the Claude connector directory listing for Contract-Factory — Sociétés & SIREN. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
