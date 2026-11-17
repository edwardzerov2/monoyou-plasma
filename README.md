# MonoYou Plasma

A collection of themes, cursors and color schemes for KDE Plasma and Konsole,
built around the three MonoYou color palettes: Cold, Neutral and Warm.

> [!WARNING]
> **Work in Progress (WIP)**
>
> MonoYou Plasma is under active development. Visual elements,
> features and compatibility may change as the project evolves.

## Available Components

| Component | Version | Cold | Neutral | Warm |
| --- | :---: | :---: | :---: | :---: |
| [Plasma Color Schemes](color-schemes/) | v1.0.0 | ✓ | ✓ | ✓ |
| [Konsole Color Schemes](konsole/) | v1.0.0 | ✓ | ✓ | ✓ |
| [Plasma Style](plasma-themes/monoyou/) | v0.1.9 | ✓ | ✓ | ✓ |
| [Cursor Themes](cursor-themes/) | v0.1.2 | ✓ | ✓ | ✓ |

Each component is versioned independently.

## Installation

### Manual Installation

Clone the repository:

```sh
git clone https://github.com/edwardzerov2/monoyou-plasma.git
cd monoyou-plasma
```

Install the available components for your current user:

```sh
data_dir="${XDG_DATA_HOME:-$HOME/.local/share}"

mkdir -p "$data_dir/color-schemes" \
         "$data_dir/konsole" \
         "$data_dir/plasma/desktoptheme" \
         "$data_dir/icons"

cp color-schemes/*.colors "$data_dir/color-schemes/"
cp konsole/*.colorscheme "$data_dir/konsole/"
cp -R plasma-themes/monoyou "$data_dir/plasma/desktoptheme/"
cp -a cursor-themes/MonoYou-Cursors-* "$data_dir/icons/"
```

### Applying the Themes

#### KDE Plasma

Open **System Settings → Plasma Style** and select **MonoYou**.

Then navigate to **Colors** and apply your preferred MonoYou variant.
The Plasma style follows the selected system color scheme.

Open **System Settings → Cursors** and select your preferred MonoYou cursor variant.

#### Konsole

Open the profile editor, navigate to **Appearance** and select
your preferred MonoYou color scheme.

## Roadmap

- [x] Plasma Color Schemes
- [x] Konsole Color Schemes
- [x] [Plasma Style](plasma-themes/monoyou/)
- [x] [Cursor Themes](cursor-themes/)
- [ ] [Application Styles](application-styles/)
- [ ] [Window Decorations](window-decorations/)
- [ ] [Global Themes](global-themes/)

## MonoYou Ecosystem

MonoYou Plasma is part of the MonoYou project, which brings a
consistent visual identity across different desktop components.

- [MonoYou Colors](https://github.com/edwardzerov2/monoyou-colors)
  — the color palettes that form the foundation of MonoYou.
- [MonoYou Folders](https://github.com/edwardzerov2/monoyou-folders)
  — Papirus-based folder icons adapted to the MonoYou palettes.

## Credits and Licensing

The MonoYou Plasma style is derived from the desktop style included
in [Darkly 0.5.44](https://github.com/Bali10050/Darkly).

The derived component retains its original
[GNU General Public License version 2](plasma-themes/monoyou/COPYING).

The cursor themes are based on [Simp1e Adw Dark](https://gitlab.com/cursors/simp1e)
and were recolored for MonoYou on November 17, 2026. They are distributed under the
[GNU General Public License version 3](cursor-themes/COPYING).

## Copyright

Copyright (c) 2026 Eduardo Rod (edwardzerov2)
