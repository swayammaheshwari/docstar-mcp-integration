# DocStar for Cursor

Connect Cursor to DocStar through the Model Context Protocol (MCP).

DocStar turns your product's API into published docs that AI assistants can
read and call. Your assistant documents each endpoint from your code, publishes
the docs, and gives you one link to share. Your users' assistants then look up
any endpoint and call your API using the exact URLs, fields, and auth from your
docs, so they don't guess.

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

## Authentication

Reading published docs needs no sign-in. Creating or changing docs needs a
DocStar sign-in via OAuth 2.0 the first time Cursor connects. No API keys are
needed, and no credentials are stored in this repository.

## Support

Open an issue in this repository.

## License

MIT - see [LICENSE](LICENSE).
