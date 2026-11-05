# Morningstar Credit Analytics

BoldCreate plugin that connects agents to Morningstar Credit Analytics through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Structured credit insights and analytics.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Morningstar Credit Analytics**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Morningstar Credit Analytics**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install morningstar-credit@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "morningstar-credit": {
      "type": "http",
      "url": "https://mcp.analytics.credit.morningstar.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Morningstar Credit Analytics in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Morningstar Credit Analytics: https://credit.morningstar.com/

## Logo

Icon taken from the vendor's website (Morningstar Credit Analytics). The site only offers a small favicon, so the image is low resolution. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
