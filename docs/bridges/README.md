# Bridges

> Bridges connect Beeper to external chat networks via the Matrix protocol.

---

## How Bridges Work

Beeper uses [Matrix](https://matrix.org/) as its core protocol. Bridges are services that translate between Matrix and other chat networks, allowing you to send and receive messages across platforms through a single app.

---

## Official Bridges

Beeper officially supports bridges for many popular networks. See [Beeper's supported networks](https://www.beeper.com/) for the full list.

Historically, Beeper maintained open-source bridges under the [mautrix](https://github.com/mautrix) organization:

| Bridge | Network | Language |
|--------|---------|----------|
| [mautrix-whatsapp](https://github.com/mautrix/whatsapp) | WhatsApp | Go |
| [mautrix-signal](https://github.com/mautrix/signal) | Signal | Go |
| [mautrix-telegram](https://github.com/mautrix/telegram) | Telegram | Python |
| [mautrix-discord](https://github.com/mautrix/discord) | Discord | Go |
| [mautrix-slack](https://github.com/mautrix/slack) | Slack | Go |
| [mautrix-gmessages](https://github.com/mautrix/gmessages) | Google Messages | Go |
| [mautrix-meta](https://github.com/mautrix/meta) | Facebook / Instagram | Go |
| [mautrix-twitter](https://github.com/mautrix/twitter) | Twitter / X | Go |

> **Note:** Since Beeper's acquisition by Automattic, some bridge architectures have changed. The mautrix bridges remain open-source and community-maintained.

---

## Community Bridges

| Bridge | ⭐ | Network | Language | Link |
|--------|----|---------|----------|------|
| imessage v2 | 23 | iMessage | Rust | [GitHub](https://github.com/lrhodin/imessage) |
| matrix-line-messenger | 14 | LINE | — | [GitHub](https://github.com/highesttt/matrix-line-messenger) |
| snapchat-bridge | 1 | Snapchat | — | [GitHub](https://github.com/lalomorales22/snapchat-bridge) |
| zalo-beeper-bridge | — | Zalo | — | [GitHub](https://github.com/lequocbinh04/zalo-beeper-bridge) |

---

## Building a Bridge

If you want to build a bridge for an unsupported network, the [mautrix](https://github.com/mautrix) libraries provide a framework:

- **Go:** [mautrix-go](https://github.com/mautrix/go)
- **Python:** [mautrix-python](https://github.com/mautrix/python)

---

*Know of a community bridge? [Share it!](https://github.com/robertogogoni/awesome-beeper/discussions/new?category=tips-discoveries)*

---

## References

<!-- Add references -->
