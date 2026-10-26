# Embarko for Cursor

Deploy and manage the apps you build with AI, straight from Cursor chat.

[Embarko](https://embarko.ai) gives apps built with AI a home online. Ask the
Cursor agent to deploy, and get a live link at `your-app.embarko.app`.

## What you can do

- Deploy static websites and one-process server apps without a Dockerfile
- Check whether an app is live and read build and runtime logs
- Set secrets and config (environment variables)
- Connect a custom domain
- Roll back to an earlier working version
- Read traffic and usage analytics
- Rename or delete an app

## Tools

| Tool              | What it does                                      |
| ----------------- | ------------------------------------------------- |
| `deploy_app`      | Deploy or update an app from its files            |
| `read_app`        | Status, logs, details, and analytics              |
| `update_app`      | Env vars, custom domain, rollback, and feedback   |
| `app_danger_zone` | Rename or delete an app, after you confirm        |

## Install

Install from the Cursor Marketplace: open **Customize**, find **Embarko**, and
select **Install**.

Or add the server manually to `~/.cursor/mcp.json`:

```json
{
  "mcpServers": {
    "embarko": {
      "url": "https://mcp.embarko.ai/mcp"
    }
  }
}
```

## Authentication

Embarko uses OAuth. The first time Cursor connects, a browser window opens so
you can sign in to Embarko. It is the same sign-in as embarko.ai. No API keys
are needed, and no credentials are stored in this repository.

## Docs and support

- Docs: https://embarko.ai/docs
- Support: https://embarko.ai/support

## License

MIT - see [LICENSE](LICENSE).
