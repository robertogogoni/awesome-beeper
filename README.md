# Awesome Beeper 🐝

> Community-driven documentation, changelogs, and resources for the Beeper ecosystem.

[![Update Status](https://github.com/robertogogoni/awesome-beeper/actions/workflows/official-updates.yml/badge.svg)](https://github.com/robertogogoni/awesome-beeper/actions/workflows/official-updates.yml)
[![GitHub Discussions](https://img.shields.io/github/discussions/robertogogoni/awesome-beeper)](https://github.com/robertogogoni/awesome-beeper/discussions)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## 📊 Status

| Component | Feed |
|-----------|------|
| Desktop App | [RSS](feeds/releases.xml) |
| SDK (`@beeper/desktop-api`) | [JSON](feeds/releases.json) |

<sub>Auto-updated daily · [How this works](docs/automation.md)</sub>

---

## 📋 Contents

- [Desktop App](#-desktop-app)
- [Official SDKs](#-official-sdks)
- [CLI Tools](#-cli-tools)
- [MCP Servers](#-mcp-servers)
- [AI & Agents](#-ai--agents)
- [Bridges](#-bridges)
- [Themes](#-themes)
- [Tools](#-tools)
- [Community](#-community)
- [Contributing](#-contributing)

---

## 🖥️ Desktop App

[Full Changelog](docs/desktop-app/changelog.md) · [Features](docs/desktop-app/features.md) · [Known Issues & Workarounds](docs/desktop-app/known-issues.md)

---

## 📦 Official SDKs

Auto-generated from the [Desktop API OpenAPI spec](https://github.com/beeper/desktop-api-cli).

| SDK | Language | ⭐ | Link |
|-----|----------|----|------|
| **desktop-api-js** | TypeScript | 21 | [GitHub](https://github.com/beeper/desktop-api-js) · [npm](https://npmjs.com/package/@beeper/desktop-api) |
| **desktop-api-python** | Python | 7 | [GitHub](https://github.com/beeper/desktop-api-python) |
| **desktop-api-go** | Go | 5 | [GitHub](https://github.com/beeper/desktop-api-go) |
| **desktop-api-php** | PHP | — | [GitHub](https://github.com/beeper/desktop-api-php) |
| **desktop-api-sql** | PLpgSQL | — | [GitHub](https://github.com/beeper/desktop-api-sql) |

> [Changelog](docs/sdk/changelog.md) · [Migration Guides](docs/sdk/migration-guides/) · [Examples](docs/sdk/examples.md)

---

## ⌨️ CLI Tools

| Tool | ⭐ | Language | Description |
|------|----|----------|-------------|
| [beepctl](https://github.com/blqke/beepctl) | 30 | TypeScript | CLI for messaging from terminal |
| [beeper-cli](https://github.com/KrauseFx/beeper-cli) | 25 | Go | Read-only browse/search chat history |
| [BeeperPS](https://github.com/AndrewPla/BeeperPS) | 8 | PowerShell | PowerShell module for Beeper API |
| [desktop-api-cli](https://github.com/beeper/desktop-api-cli) | 5 | Go | Official Beeper CLI (v0.2.0) `[official]` |
| [beeper-cli](https://github.com/foeken/beeper-cli) | 2 | Go | CLI for Desktop API |
| [beeper-api-cli](https://github.com/nerveband/beeper-api-cli) | — | Go | Cross-platform CLI |
| [beeper-messaging-tools](https://github.com/mimen/beeper-messaging-tools) | 1 | TypeScript | Web app for Desktop API |

---

## 🤖 MCP Servers

Model Context Protocol servers for AI assistant integration.

| Server | ⭐ | Description |
|--------|----|-------------|
| [desktop-api-mcp](https://github.com/beeper/desktop-api-mcp) | 3 | Official Claude Desktop Extension `[official]` |
| [mcp-android](https://github.com/beeper/mcp-android) | 8 | Android MCP server `[official]` |
| [Beeper KB](https://github.com/robertogogoni/beeper-kb) | — | Knowledge base MCP server for Beeper docs |
| [poke-beeper-proxy](https://github.com/keithah/poke-beeper-proxy) | 1 | macOS tunneling proxy for Desktop API |
| [beeper-mcp](https://github.com/mimen/beeper-mcp) | — | Python MCP server |

---

## 🧠 AI & Agents

| Project | Description |
|---------|-------------|
| [agentremote](https://github.com/beeper/agentremote) | Official AI agent platform — Codex, OpenClaw, and OpenCode bridges `[official]` |
| [chat-adapter-matrix](https://github.com/beeper/chat-adapter-matrix) | Vercel Chat SDK adapter for all bridged networks `[official]` |
| [CodeBeep](https://github.com/Mihai-Codes/CodeBeep) | AI coding agent via Matrix/Beeper + OpenCode |
| [linkedin-spam-filter](https://github.com/manthis/linkedin-spam-filter) | OpenClaw skill for LinkedIn spam filtering |

---

## 🌉 Bridges

Bridges connect Beeper to external chat networks via the Matrix protocol.

### Official Bridges

See [Beeper's supported networks](https://www.beeper.com/) for the full list of officially maintained bridges.

### Community Bridges

| Bridge | ⭐ | Network | Language |
|--------|----|---------|----------|
| [imessage v2](https://github.com/lrhodin/imessage) | 23 | iMessage | Rust |
| [matrix-line-messenger](https://github.com/highesttt/matrix-line-messenger) | 14 | LINE | — |
| [snapchat-bridge](https://github.com/lalomorales22/snapchat-bridge) | 1 | Snapchat | — |
| [zalo-beeper-bridge](https://github.com/lequocbinh04/zalo-beeper-bridge) | — | Zalo | — |

> [Full Bridges Documentation](docs/bridges/README.md)

---

## 🎨 Themes

| Theme | ⭐ | Description |
|-------|----|-------------|
| [themes](https://github.com/beeper/themes) | 156 | Official community themes (CSS) `[official]` |
| [Metrology-for-Beeper](https://github.com/Madelena/Metrology-for-Beeper) | 41 | Flat Metro design |
| [beeper-custom-css](https://github.com/clins1994/beeper-custom-css) | 11 | Custom CSS styles |
| [beeper-midnight](https://github.com/JaxonWright/beeper-midnight) | 8 | Pitch-black dark theme |
| [beeper-icons-theme](https://github.com/MoralesJonathan/beeper-icons-theme) | 5 | Full color social media icons |
| [Beeper-WinUI-Theme](https://github.com/highesttt/Beeper-WinUI-Theme) | 4 | WinUI 3 theme |

---

## 🛠️ Tools

| Tool | ⭐ | Description |
|------|----|-------------|
| [docker-beeper](https://github.com/zachatrocity/docker-beeper) | 56 | Self-hosted Beeper Desktop in browser |
| [update-beeper](https://github.com/beeper-community/update-beeper) | — | Self-healing Linux updater with AUR fallback |
| [Beeper-install](https://github.com/nzxlabs/Beeper-install) | 8 | Easy-install scripts |
| [beepex](https://github.com/johnburnett/beepex) | 3 | Export Beeper chat history |
| [beeper-chat-monitor](https://github.com/aaamgi/beeper-chat-monitor) | 3 | Windows tray chat monitor |
| [beeper-message-sync](https://github.com/prime-radiant-inc/beeper-message-sync) | 2 | Sync chat history to JSONL |
| [beeper-wsl-proxy](https://github.com/BosTheCoder/beeper-wsl-proxy) | — | WSL proxy for Desktop API |
| [Raycast Extension](https://github.com/beeper/raycast) | — | Search/manage Beeper from Raycast `[official]` |

> [All Community Tools](docs/community/tools.md)

---

## 👥 Community

Curated tips, tricks, and discoveries from the Beeper community.

> [Tips & Tricks](docs/community/tips-and-tricks.md)
> [Developer Chat Highlights](docs/community/developer-chat/)
> [Third-Party Tools](docs/community/tools.md)

### Source Tags

| Tag | Meaning |
|-----|---------|
| `[official]` | From Beeper team or official docs |
| `[community]` | Verified by community testing |
| `[unverified]` | Needs confirmation |

---

## 🔔 Stay Updated

- **RSS Feed:** [feeds/releases.xml](feeds/releases.xml)
- **JSON Feed:** [feeds/releases.json](feeds/releases.json)

---

## 🤝 Contributing

We welcome contributions! See [CONTRIBUTING.md](CONTRIBUTING.md) for guidelines.

- 💬 **Share a discovery** → [Start a Discussion](https://github.com/robertogogoni/awesome-beeper/discussions/new?category=tips-discoveries)
- 📝 **Improve docs** → [Submit a PR](https://github.com/robertogogoni/awesome-beeper/pulls)
- 🐛 **Report an issue** → [Open an Issue](https://github.com/robertogogoni/awesome-beeper/issues)

---

## 📜 License

MIT © [Awesome Beeper Contributors](https://github.com/robertogogoni/awesome-beeper/graphs/contributors)

---

<sub>
This project is not affiliated with Beeper or Automattic.
Built with ❤️ by the Beeper community.
</sub>
