# dotfiles

Arch Linux · Hyprland · Nord

## Setup

| Role | Tool |
|---|---|
| WM | Hyprland (master layout) |
| Bar | Waybar + Cava |
| Terminal | Kitty |
| Shell | Bash / Zsh + Starship |
| Editor | Neovim (LazyVim) |
| Launcher | Rofi |
| File manager | Yazi |
| Notifications | Mako |
| Lock / Idle | Hyprlock + Hypridle |
| Wallpaper | Hyprpaper |
| Theme | Nord |

## Structure

```
.
├── .bashrc / .bash_profile / .zshrc
├── .config/
│   ├── hypr/          # hyprland, hyprlock, hypridle, hyprpaper
│   ├── waybar/        # config, styles, scripts, modules
│   ├── kitty/         # kitty + nord theme
│   ├── nvim/          # LazyVim config
│   ├── rofi/          # launcher theme
│   ├── yazi/          # file manager config
│   ├── eww/           # widget config
│   ├── starship/      # prompt themes (nord + dracula)
│   ├── fastfetch/     # fetch config + logo
│   ├── btop/          # system monitor
│   ├── cava/          # audio visualizer
│   └── scripts/       # misc helper scripts
└── .gtkrc-2.0
```

## Install

Clone and symlink (or copy) files to their respective locations under `$HOME`.
