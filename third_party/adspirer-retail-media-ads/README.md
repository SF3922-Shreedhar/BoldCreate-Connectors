# Adspirer Retail Media Ads

BoldCreate plugin that connects agents to Adspirer Retail Media Ads through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Retail media agent for Amazon Ads and Walmart Connect — Sponsored Products, Sponsored Brands and Sponsored Display. Plans, launches, and optimizes your retail advertising campaigns with your approval.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Adspirer Retail Media Ads**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Adspirer Retail Media Ads**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install adspirer-retail-media-ads@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "adspirer-retail-media-ads": {
      "type": "http",
      "url": "https://mcp.adspirer.com/retail-ads"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Adspirer Retail Media Ads in the browser (OAuth). Tool calls run with that member's permissions.

The endpoint comes from the Claude connector directory. An anonymous request returned a 401 without OAuth metadata, so the server is reachable and asks for credentials, but the sign-in method is an assumption. No tool call has been made.

## Docs

- Adspirer Retail Media Ads: https://www.adspirer.com/

## Logo

Icon downloaded from the Claude connector directory listing for Adspirer Retail Media Ads. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
