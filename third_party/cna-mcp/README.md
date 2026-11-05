# 中央社新聞 CNA TAIWAN NEWS

BoldCreate plugin that connects agents to 中央社新聞 CNA TAIWAN NEWS through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

把中央社可信新聞接進你的 AI｜Taiwan CNA news, sourced answers.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **中央社新聞 CNA TAIWAN NEWS**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **中央社新聞 CNA TAIWAN NEWS**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install cna-mcp@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "cna-mcp": {
      "type": "http",
      "url": "https://ask.cna.com.tw/mcp/connect"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to 中央社新聞 CNA TAIWAN NEWS in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- 中央社新聞 CNA TAIWAN NEWS: https://ask.cna.com.tw/ask

## Logo

Icon downloaded from the Claude connector directory listing for 中央社新聞 CNA TAIWAN NEWS. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
