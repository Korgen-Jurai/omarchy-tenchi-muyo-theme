# Omarchy Tenchi Muyo Theme

Tenchi Muyo is a dark palette sampled directly from the *Tenchi Ultrawide* wallpaper: a deep indigo-navy background pulled from the jacket, a bright sky-blue accent from the clouds, and a warm crimson red from the emblem. Gaps, corner rounding, and animations are all matched to the X-1632 theme (`gaps_in = 6`, `gaps_out = 8`, `rounding = 22`, `rounding_power = 1`).

## Preview

![Theme preview](preview.png)

## Install

```bash
omarchy theme install https://github.com/Korgen-Jurai/omarchy-tenchi-muyo-theme.git
```

## What's included

- Terminal palette (`colors.toml`) — drives Alacritty, Kitty, Foot, Ghostty, btop, VS Code, Obsidian, and more via Omarchy's built-in templates
- Hyprland gaps/borders/rounding/animations (`hyprland.conf`, `hyprland.lua`)
- Icon theme pointer (`icons.theme` → Yaru-blue-dark)
- Wallpaper (`backgrounds/1-tenchi-muyo.jpg`)

## Wallpaper

![Tenchi Ultrawide wallpaper](backgrounds/1-tenchi-muyo.jpg)

## Multi-monitor crops (bonus, not auto-installed)

Omarchy renders one shared, centered-crop wallpaper across every monitor, which can crop the subject out on non-16:9 or portrait displays. `backgrounds/portrait-dp2.jpg` and `backgrounds/tv-hdmi-a-1.jpg` are alternate crops of the same source image, framed for a 1080x1920 portrait display and a 16:9 TV respectively. They're applied via a second, per-output `hyprpaper` instance layered on top of Omarchy's own background on just those outputs — see `~/.config/hypr/hyprpaper.conf` and the `hyprpaper` line in `~/.config/hypr/autostart.lua` on the machine this was built on. Not wired into the theme's install flow since it's monitor-layout specific.
