# Keelson

**Deploy apps built with AI tools to the web — with login built in.**

[Keelson](https://keelson.dev) runs the internal apps your team builds with Claude, ChatGPT, Manus, Lovable, Bolt, v0, or your own tools. Every app is private by default: only signed-in members you choose can open it, and you never write authentication code yourself.

- **Login built in** — unauthenticated requests never reach your app. See [how login works](https://keelson.dev/docs/access-control/auth-and-login/) and [members and permissions](https://keelson.dev/docs/access-control/members-and-permissions/).
- **One isolated service per app** — each app runs as its own private container. See [how apps run](https://keelson.dev/docs/building-apps/how-apps-run/).
- **Managed SQLite** — a persistent database per app, with restore. See [persistent storage](https://keelson.dev/docs/building-apps/persistent-storage/) and [update and restore](https://keelson.dev/docs/deploy/update-and-restore/).
- **Deploy from your AI coding agent** — an Agent Skill for Claude Code, Codex, and Cursor.

## Quickstart

```sh
# macOS / Linux
curl -fsSL https://keelson.dev/install.sh | sh
```

```powershell
# Windows
irm https://keelson.dev/install.ps1 | iex
```

```sh
keelson login
keelson install-agent claude-code --global   # or: codex, cursor
keelson deploy --new
```

The full walkthrough takes about 15 minutes: **[Quickstart](https://keelson.dev/docs/introduction/quickstart/)**.

## Documentation

| Start here | Build | Reference |
| --- | --- | --- |
| [What is Keelson](https://keelson.dev/docs/introduction/what-is-keelson/) | [Bring an existing app](https://keelson.dev/docs/building-apps/bring-your-app/) | [CLI commands](https://keelson.dev/docs/reference/cli/) |
| [Core concepts](https://keelson.dev/docs/introduction/core-concepts/) | [Supported app types](https://keelson.dev/docs/building-apps/supported-app-types/) | [keelson.yaml reference](https://keelson.dev/docs/reference/keelson-yaml-reference/) |
| [Quickstart](https://keelson.dev/docs/introduction/quickstart/) | [Frameworks](https://keelson.dev/docs/building-apps/frameworks/) | [Deploy spec](https://keelson.dev/docs/reference/deploy-spec/) |
| [FAQ](https://keelson.dev/docs/introduction/faq/) | [Scheduled jobs](https://keelson.dev/docs/building-apps/scheduled-jobs/) | [Environment variables](https://keelson.dev/docs/reference/environment-variables/) |
| [Plans and limits](https://keelson.dev/docs/workspace/plans-and-limits/) | [Files and media](https://keelson.dev/docs/building-apps/files-and-media/) | [Error codes](https://keelson.dev/docs/reference/error-codes/) |

Asking an AI tool about Keelson? Point it at [`keelson.dev/llms.txt`](https://keelson.dev/llms.txt). 日本語のドキュメントは [keelson.dev/ja/docs](https://keelson.dev/ja/docs/) にあります。

## Repositories

| Repository | What it is |
| --- | --- |
| [node-sdk](https://github.com/keelsonhq/node-sdk) · [python-sdk](https://github.com/keelsonhq/python-sdk) · [go-sdk](https://github.com/keelsonhq/go-sdk) | SDKs for apps running on Keelson — identity, media, files, and email. [SDK guide](https://keelson.dev/docs/building-apps/sdk/) |
| [ai-chat](https://github.com/keelsonhq/ai-chat) · [ai-chat-ja](https://github.com/keelsonhq/ai-chat-ja) | AI chat template, ready to deploy. More on the [templates page](https://keelson.dev/templates/) |
| [sqlalchemy-libsql-native](https://github.com/keelsonhq/sqlalchemy-libsql-native) | SQLAlchemy dialect for libSQL |

## Links

[Website](https://keelson.dev) · [Docs](https://keelson.dev/docs/introduction/what-is-keelson/) · [Pricing](https://keelson.dev/pricing/) · [Trust](https://keelson.dev/trust/) · [Blog](https://keelson.dev/blog/) · [Contact](https://keelson.dev/contact/)
