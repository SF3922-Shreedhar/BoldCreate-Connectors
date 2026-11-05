# Community Funding NZ

BoldCreate plugin that connects agents to Community Funding NZ through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search 380+ New Zealand community grant funders, with deadlines, priorities and application questions, so your AI can find funders and draft applications.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Community Funding NZ**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Community Funding NZ**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install community-funding-nz@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "community-funding-nz": {
      "type": "http",
      "url": "https://funding.alltoohuman.nz/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Community Funding NZ: https://www.alltoohuman.nz/

## Logo

Neutral tile with the product's initials.

## License

MIT
