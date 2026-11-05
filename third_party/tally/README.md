# Tally

BoldCreate plugin that connects agents to Tally through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Create beautiful forms.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tally**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tally**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tally@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tally": {
      "type": "http",
      "url": "https://api.tally.so/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Tally in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Tally: https://tally.so/

## Logo

Icon downloaded from the Claude connector directory listing for Tally. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
