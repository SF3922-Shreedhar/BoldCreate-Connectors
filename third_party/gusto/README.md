# Gusto

BoldCreate plugin that connects agents to Gusto through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Query and analyze your Gusto data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Gusto**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Gusto**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install gusto@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "gusto": {
      "type": "http",
      "url": "https://mcp.api.gusto.com/anthropic"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Gusto in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Gusto: https://gusto.com/

## Logo

Icon downloaded from the Claude connector directory listing for Gusto, converted to PNG and centred on a white tile. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.}

## License

MIT
