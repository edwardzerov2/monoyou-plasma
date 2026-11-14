# MonoYou Plasma

MonoYou color schemes and themes for KDE Plasma and Konsole.

## Available

- [KDE color schemes](color-schemes/) for MonoYou Neutral, Cold and Warm.
- [MonoYou Slate](konsole/) for Konsole.

To install the schemes for your user, run these commands from the project root.

```sh
data_dir="${XDG_DATA_HOME:-$HOME/.local/share}"
mkdir -p "$data_dir/color-schemes" "$data_dir/konsole"
cp color-schemes/*.colors "$data_dir/color-schemes/"
cp konsole/*.colorscheme "$data_dir/konsole/"
```

Select a KDE scheme under **System Settings → Colors**. In Konsole, open the profile editor and select **MonoYou Slate** under **Appearance**.

## In development

- [Plasma desktop themes](plasma-themes/)
- [Application styles](application-styles/)
- [Window decorations](window-decorations/)
- [Global themes](global-themes/)

Screenshots and other images go in [assets/images/](assets/images/). GitHub configuration goes in [.github/](.github/).
