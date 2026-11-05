# Ramp

BoldCreate plugin that connects agents to Ramp through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Search, access, and analyze your Ramp financial data.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Ramp**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Ramp**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install ramp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "ramp": {
      "type": "http",
      "url": "https://ramp-mcp-remote.ramp.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Ramp in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Ramp: https://ramp.com/

## Logo

Icon downloaded from the Claude connector directory listing for Ramp. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
