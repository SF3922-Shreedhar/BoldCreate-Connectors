# Elfcare

BoldCreate plugin that connects agents to Elfcare through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Explore your Elfcare test results.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Elfcare**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Elfcare**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install elfcare@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "elfcare": {
      "type": "http",
      "url": "https://patient.elf.care/api/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Elfcare in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Elfcare: https://elf.care/

## Logo

Icon downloaded from the Claude connector directory listing for Elfcare. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
