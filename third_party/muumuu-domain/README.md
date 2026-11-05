# MuuMuu Domain byGMO Pepabo

BoldCreate plugin that connects agents to MuuMuu Domain byGMO Pepabo through the vendor's hosted [Model Context Protocol](https://modelcontextprotocol.io/) server over streamable HTTP.

ムームードメインと接続し、ドメインの空き検索・価格確認から購入手続きまでを会話で進められます。決済はムームードメインのサイト上でご自身が完了させる方式です。保有ドメインの一覧・詳細確認、ネームサーバーの確認・変更、DNSレコードの一覧・作成・更新・削除、更新日や自動更新設定の確認・変更にも対応します。.

## Install

- **BoldCreate Connect:** open **Marketplace**, find **MuuMuu Domain byGMO Pepabo**, and click **Install**.
- **Cursor:** add this repository as a team marketplace, then install **MuuMuu Domain byGMO Pepabo**.
- **Claude Code:** `/plugin marketplace add SF3922-Shreedhar/BoldCreate-Connectors`, then `/plugin install muumuu-domain@boldcreate-connectors`.

## MCP

```json
{
  "mcpServers": {
    "muumuu-domain": {
      "type": "http",
      "url": "https://mcp.muumuu-domain.com/mcp"
    }
  }
}
```

## Setup

No settings.

The first time the agent calls a tool, each member signs in to MuuMuu Domain byGMO Pepabo in the browser (OAuth). Tool calls run with that member's permissions.

## Docs

- MuuMuu Domain byGMO Pepabo: https://muumuu-domain.com/

## Logo

Icon downloaded from the Claude connector directory listing for MuuMuu Domain byGMO Pepabo. It is the vendor's own icon and a trademark of its owner. It is not covered by the MIT licence.

## License

MIT
