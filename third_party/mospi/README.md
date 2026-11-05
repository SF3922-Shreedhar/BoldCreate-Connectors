# MoSPI

BoldCreate plugin that connects agents to MoSPI through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

India's official statistics via natural language.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MoSPI**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MoSPI**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install mospi@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "mospi": {
      "type": "http",
      "url": "https://mcp.mospi.gov.in/"
    }
  }
}
```

## Setup

No settings.

The server answered anonymous requests without asking for sign-in, so no account is needed to connect. Some tools may still need one.

The endpoint comes from the Claude connector directory. An anonymous initialize and tools/list request returned a tool list. No tool was called.

## Docs

- MoSPI: https://www.mospi.gov.in/

## Logo

Icon taken from the vendor's website (MoSPI). The site only offers a small favicon, so the image is low resolution. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
