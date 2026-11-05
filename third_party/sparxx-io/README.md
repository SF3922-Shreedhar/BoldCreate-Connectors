# spArxx.io | Zero-Knowledge Blockchain Timestamping

BoldCreate plugin that connects agents to spArxx.io | Zero-Knowledge Blockchain Timestamping through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Prove you made it first. Timestamp your creative work on the blockchain via Claude or any MCP-enabled AI agent.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **spArxx.io | Zero-Knowledge Blockchain Timestamping**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **spArxx.io | Zero-Knowledge Blockchain Timestamping**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install sparxx-io@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "sparxx-io": {
      "type": "http",
      "url": "https://gateway.sparxx.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to spArxx.io | Zero-Knowledge Blockchain Timestamping in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- spArxx.io | Zero-Knowledge Blockchain Timestamping: https://www.sparxx.io/

## Logo

Icon downloaded from the Claude connector directory listing for spArxx.io | Zero-Knowledge Blockchain Timestamping. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
