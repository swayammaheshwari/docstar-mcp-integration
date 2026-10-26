# DocStar for Cursor

Connect Cursor to DocStar through the Model Context Protocol (MCP).

## What it does

DocStar turns your product's API into published docs that AI assistants can
read and call. This plugin gives Cursor access to the DocStar MCP server so the
agent can work with your DocStar docs directly from the editor.

## Install

Install from the Cursor Marketplace: open **Customize**, find **DocStar**, and
select **Install**.

Or add the server manually to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "docstar": {
      "url": "https://mcp.docstar.io/mcp"
    }
  }
}
```

## Components

| Component  | Description                                         |
| ---------- | --------------------------------------------------- |
| MCP server | `docstar` - remote MCP server at `mcp.docstar.io`   |

## Authentication

DocStar uses OAuth 2.0. The first time Cursor connects, a browser window opens
so you can sign in with your DocStar account. No API keys are needed, and no
credentials are stored in this repository.

## Support

Open an issue in this repository.

## License

MIT - see [LICENSE](LICENSE).
