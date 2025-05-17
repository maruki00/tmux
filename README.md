# Tmux Configuration Guide

This configuration customizes and enhances `tmux` with Vim-style navigation, plugin support, theming, and an intuitive menu system. Ideal for developers who want a productive, visually appealing terminal workflow.

---

## Key Features

### Prefix Key Change
- **New prefix**: `Ctrl + Space` (`C-Space`)
- Replaces the default `Ctrl + b` for a more ergonomic experience.

### Reload Configuration
- **Shortcut**: Press `Prefix + r` to reload the config and see changes instantly.
- Displays a message on success.

### Plugin Manager: TPM
- Managed using [TPM (Tmux Plugin Manager)](https://github.com/tmux-plugins/tpm)
- Plugins used:
  - `tmux-plugins/tpm`: Plugin manager
  - `arl/tmux-menus`: Interactive menus
  - `dracula/tmux`: Dracula theme with powerline and weather integration

### Vim-style Pane Navigation
- Navigate between panes using:
  - `h/left arrow` (left)
  - `j/down arrow` (down)
  - `k/up arrow` (up)
  - `l/right arrow` (right)

### Mouse Support
- Click to switch panes, resize, and interact.

### Dracula Theme
- Beautiful Dracula theme with powerline.
- Customizations:
  - Location: `Tangier`
  - Plugins shown: `weather`
  - Left icon: Session indicator
  - Flags and top-aligned status bar

## Tmux Menus
- Press `Prefix + m` to open an interactive menu:
  - Create and split windows
  - Switch/list windows
  - Reload config
  - Detach session

### Mighty Scroll Plugin (Not included via TPM)
> Configuration lines are included for `mighty-scroll`, but make sure to install it manually or remove those lines if unused.

---

## Installing Plugins

1. Start tmux:  
   ```bash
   tmux
   Prefix + I
  ```
