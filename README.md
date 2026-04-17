# wilfoa-plugins

Personal [Claude Code](https://docs.claude.com/claude-code) plugin marketplace.

> **Note:** The marketplace name is `wilfoa-plugins`, but this repository is named `claude-plugins`. Use `wilfoa/claude-plugins` (the repo) when *adding* the marketplace, and `@wilfoa-plugins` (the marketplace name) when *installing* plugins from it.

## Plugins

| Plugin | Description | Source |
|--------|-------------|--------|
| `telegram-topics` | Telegram channel with Forum Topics — each Claude Code project gets its own topic thread. Pairing, allowlists, and per-project topic naming via plugin commands. | [wilfoa/claude-telegram-topics](https://github.com/wilfoa/claude-telegram-topics) |

## Usage

```bash
# Add this marketplace (uses the repo name)
/plugin marketplace add wilfoa/claude-plugins

# Install a plugin (uses the marketplace name)
/plugin install telegram-topics@wilfoa-plugins
```
