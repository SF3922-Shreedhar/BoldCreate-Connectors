# Maryland Community Compass

BoldCreate plugin that connects agents to Maryland Community Compass through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Maryland's neighborhood development data platform.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Maryland Community Compass**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Maryland Community Compass**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install maryland-compass@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "maryland-compass": {
      "type": "http",
      "url": "https://compass.maryland.gov/mcp/"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- Maryland Community Compass: https://innovation.maryland.gov/Pages/default.aspx

## Logo

Icon downloaded from the Claude connector directory listing for Maryland Community Compass. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
