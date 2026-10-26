# Cursor plugins

Cursor plugins for our products. This is a multi-plugin repository: the root
`.cursor-plugin/marketplace.json` lists every plugin, and each plugin has its
own folder and manifest.

| Plugin | What it does |
| ------ | ------------ |
| [docstar](docstar) | Publish API docs your users' AI assistants can read and call |
| [embarko](embarko) | Instant hosting for apps you build with AI |

## Structure

```
.cursor-plugin/marketplace.json
docstar/   .cursor-plugin/plugin.json, mcp.json, README.md, LICENSE
embarko/   .cursor-plugin/plugin.json, mcp.json, README.md, LICENSE
```

## License

MIT - see [LICENSE](LICENSE).
