# MonoYou Plasma

A collection of color schemes and themes for KDE Plasma and Konsole, built around the MonoYou color palettes.

> [!WARNING]
> **Work in Progress (WIP)**
>
> MonoYou Plasma is currently under active development.
> Visual elements, features and compatibility may change over time.

## Available Themes

| Component | Variants |
| --- | --- |
| [KDE Color Schemes](color-schemes/) | Cold, Neutral, Warm |
| [Konsole Color Schemes](konsole/) | Slate |

## Installation

### Manual Installation

Clone the repository:

```sh
git clone https://github.com/edwardzerov2/monoyou-plasma.git
cd monoyou-plasma
```

Install the color schemes for your user:

```sh
data_dir="${XDG_DATA_HOME:-$HOME/.local/share}"

mkdir -p "$data_dir/color-schemes" "$data_dir/konsole"

cp color-schemes/*.colors "$data_dir/color-schemes/"
cp konsole/*.colorscheme "$data_dir/konsole/"
```

### Applying the Themes

**KDE Plasma**

Open **System Settings → Colors**, select your preferred MonoYou variant and apply it.

**Konsole**

Open the profile editor, navigate to **Appearance** and select **MonoYou Slate**.

## Roadmap

- [x] KDE Color Schemes
- [x] Konsole Color Schemes
- [ ] [Plasma Desktop Themes](plasma-themes/)
- [ ] [Application Styles](application-styles/)
- [ ] [Window Decorations](window-decorations/)
- [ ] [Global Themes](global-themes/)

## Related Projects

- [MonoYou Colors](https://github.com/edwardzerov2/monoyou-colors)
- [MonoYou Folders](https://github.com/edwardzerov2/monoyou-folders)

## Copyright

Copyright (c) 2026 Eduardo Rod (edwardzerov2)
