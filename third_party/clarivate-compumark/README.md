# Clarivate IPOne CompuMark Trademarks

BoldCreate plugin that connects agents to Clarivate IPOne CompuMark Trademarks through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Trusted Trademark Intelligence from Clarivate CompuMark.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Clarivate IPOne CompuMark Trademarks**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Clarivate IPOne CompuMark Trademarks**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install clarivate-compumark@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "clarivate-compumark": {
      "type": "http",
      "url": "https://ipone.clarivate.com/trademarks/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Clarivate IPOne CompuMark Trademarks in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Clarivate IPOne CompuMark Trademarks: https://clarivate.com/

## Logo

Icon downloaded from the Claude connector directory listing for Clarivate IPOne CompuMark Trademarks. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
