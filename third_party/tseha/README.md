# Tseha.io

BoldCreate plugin that connects agents to Tseha.io through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Your coding standards, live in Claude.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Tseha.io**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Tseha.io**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install tseha@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "tseha": {
      "type": "http",
      "url": "https://tseha.io/mcp"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Tseha.io: https://tseha.io/

## Logo

Icon taken from the vendor's website (Tseha.io). It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
