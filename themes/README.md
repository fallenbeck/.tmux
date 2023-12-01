# tmux color schemes

## Catppuccin

https://github.com/catppuccin/tmux

```bash
THEMES_DIR=$HOME/.config/tmux/themes
for flavor in frappe latte macchiato mocha; do
    curl -O \
        https://raw.githubusercontent.com/catppuccin/tmux/main/catppuccin-$flavor.tmuxtheme \
        --create-dirs \
        -o $THEMES_DIR/catppuccin-$flavor.tmuxtheme
done
```

