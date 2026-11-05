# Internet Computer

BoldCreate plugin that connects agents to Internet Computer through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Ask questions and perform actions across Internet Computer (ICP) apps using your Internet Identity.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Internet Computer**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Internet Computer**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install icp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "icp": {
      "type": "http",
      "url": "https://mcp.internetcomputer.org/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Internet Computer in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Internet Computer: https://dfinity.org/

## Logo

Neutral tile with the product's initials.

## License

MIT
