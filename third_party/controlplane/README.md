# Control Plane

BoldCreate plugin that connects agents to Control Plane through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Deploy, scale, and debug cloud apps from one platform.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Control Plane**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Control Plane**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install controlplane@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "controlplane": {
      "type": "http",
      "url": "https://mcp.cpln.io/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Control Plane in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Control Plane: https://controlplane.com/

## Logo

Icon downloaded from the Claude connector directory listing for Control Plane. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
