# autoTheme

This script acts as an extension to wal, by taking the generated colors and theming anything that can be themed, all in one script. 

If the script detects you have certain programs on your system, it will try to generate themes for them.

The current programs are ones that I use, but feel free to add more and send a PR!

## Installation

```bash
git clone https://github.com/GideonWolfe/autoTheme/
cd autoTheme
sudo ./install.sh
```

## Usage

`theme [path to picture] [options for wal]`

There are so many programs called from this script, it is easier to just edit the script to change the flags to your liking. for example, `wal_steam` is set to always use the `-w` option to take colors from wal. If you would rather use `-g` for a wpgtk theme, just change it in the script.

## Programs supported
[oomox](https://github.com/themix-project/oomox) for GTK and Spotify

[Zathura-Pywal](https://github.com/GideonWolfe/Zathura-Pywal)

[Gnuplot-Pywal](https://github.com/GideonWolfe/Gnuplot-Pywal)

[wal_steam](https://github.com/kotajacob/wal_steam) for steam

[ckb-next](https://github.com/ckb-next/ckb-next) for corsair keyboards

[telegram-palette-gen](https://github.com/matgua/telegram-palette-gen) for telegram-desktop

## Planned support
DuckDuckGo search colors

## Notes
To get the most complete theme possible, check out my [dotfiles](https://github.com/GideonWolfe/PC-dotfiles). Here you can find the configurations to get these colors on many other programs, such as rofi, polybar, firefox, and more. Since they update automatically, there was no need to include them in this script.

To apply icon themes, you need one of the icon sets supported by oomox. Change the icons section of the script to look for the folder your desired icons are in, and change the command to the appropriate variant.

* [gnome-color-icons](https://aur.archlinux.org/packages/gnome-colors-icon-theme/)
* [archdroid icons](https://aur.archlinux.org/packages/archdroid-icon-theme/)
* [Materia icons](https://aur.archlinux.org/packages/materia-theme-git/)
