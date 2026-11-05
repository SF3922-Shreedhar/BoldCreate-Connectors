# Legal Brain Agent

BoldCreate plugin that connects agents to Legal Brain Agent through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

日本最大級の法律データベースを基盤にした、法務特化AIエージェント.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Legal Brain Agent**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Legal Brain Agent**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install legal-brain-agent@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "legal-brain-agent": {
      "type": "http",
      "url": "https://api.legalbrain.com/v1/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Legal Brain Agent in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Legal Brain Agent: https://www.bengo4.com/corporate/

## Logo

Neutral tile with the product's initials.

## License

MIT
