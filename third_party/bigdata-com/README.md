# Bigdata.com

BoldCreate plugin that connects agents to Bigdata.com through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Financial news, SEC filings, earnings call transcripts, fundamentals, sentiment, market data and stock research for AI, with every answer cited. The sources that move markets.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Bigdata.com**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Bigdata.com**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install bigdata-com@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "bigdata-com": {
      "type": "http",
      "url": "https://mcp.bigdata.com/"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Bigdata.com in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Bigdata.com: https://www.ravenpack.com/

## Logo

Icon taken from the vendor's website (Bigdata.com), because the Claude connector directory links to a web page instead of an image file. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
