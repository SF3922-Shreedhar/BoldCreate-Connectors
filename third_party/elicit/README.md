# Elicit

BoldCreate plugin that connects agents to Elicit through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search and analyze scientific papers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Elicit**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Elicit**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install elicit@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "elicit": {
      "type": "http",
      "url": "https://elicit.com/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Elicit in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Elicit: https://elicit.com/

## Logo

Icon downloaded from the Claude connector directory listing for Elicit. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
