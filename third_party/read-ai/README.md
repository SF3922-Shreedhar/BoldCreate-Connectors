# Read AI

BoldCreate plugin that connects agents to Read AI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Bring your meetings into Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Read AI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Read AI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install read-ai@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "read-ai": {
      "type": "http",
      "url": "https://api.read.ai/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Read AI in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 with OAuth metadata, so the server is reachable and asks for sign-in. No tool call has been made.

## Docs

- Read AI: https://read.ai/

## Logo

Icon downloaded from the Claude connector directory listing for Read AI. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
