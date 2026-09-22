# herdr config

My [herdr](https://github.com/herdrdev/herdr) config: tmux-style keys for panes and tabs.

## Install

Backs up your current config (if any) with a timestamp, then downloads this one:

```sh
f=~/.config/herdr/config.toml; mkdir -p ~/.config/herdr; [ -f "$f" ] && cp "$f" "$f.bak.$(date +%Y%m%d-%H%M%S)"
curl -fsSL https://raw.githubusercontent.com/stellarthemes/herdr-config/main/config.toml -o "$f"
```

To undo, copy the `.bak` file back over `config.toml`.

## Shortcuts

Prefix is `ctrl+\`.

| Action | Keys |
|---|---|
| Split side by side | `prefix v`, `ctrl+left`, `ctrl+right` |
| Split top/bottom | `prefix -`, `ctrl+up`, `ctrl+down` |
| Focus pane left/right/up/down | `prefix h/l/k/j`, `shift+arrows` |
| Zoom pane | `prefix z`, `alt+e` |
| Next / previous tab | `prefix n` / `prefix p`, `alt+right` / `alt+left` |
| Jump to last pane | `prefix \` |
| lazygit popup (needs lazygit) | `prefix i` |

Theme follows the terminal's light/dark mode (dracula / solarized). New tabs open without asking for a name.
