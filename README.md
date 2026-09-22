# herdr config

My [herdr](https://github.com/herdrdev/herdr) config: tmux-style keys for panes and tabs.

## Install

```sh
mkdir -p ~/.config/herdr
cp config.toml ~/.config/herdr/config.toml
```

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
