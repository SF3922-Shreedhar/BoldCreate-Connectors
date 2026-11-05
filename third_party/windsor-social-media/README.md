# Windsor.ai for Social Media

BoldCreate plugin that connects agents to Windsor.ai for Social Media through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

Analyze and post organic social content across Instagram, Facebook, TikTok, YouTube, LinkedIn, and Google Business Profile.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **Windsor.ai for Social Media**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **Windsor.ai for Social Media**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install windsor-social-media@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "windsor-social-media": {
      "type": "http",
      "url": "https://mcp.windsor.ai/social_media"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to Windsor.ai for Social Media in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- Windsor.ai for Social Media: https://windsor.ai/

## Logo

Neutral tile with the product's initials.

## License

MIT
