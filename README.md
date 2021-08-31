## About
striknina's GTK themes collection, also including icons and terminal colours for good measure. Mostly sweeping recolours of the Arc GTK theme.

A little heads up: this is for the most part a personal collection, so the themes have been built tailored to the DEs that I use. That means no Cinnamon and GNOME support, at least for the time being. Fret not, though - I've packed the Oomox colours, which can be found in the /oomox-colours directory, in case you'd like to build the themes yourself.

(I'll make sure to contribute my colourschemes to the original Oomox theme builder!)

## Installation

Clone the repository onto your device:

```
git clone https://github.com/striknina/gtk-themes.git
```

(or download the zip file, if you so prefer.)

Themes can be installed by copying the theme folders into `~/.themes` for a user-wide install or `/usr/share/themes` for a system-wide install.

Icons can be installed by copying the icon folders into `~/.icons` for a user-wide install or `/usr/share/icons` for a system-wide install.

(System-wide install ensures that the theme you've chosen also applies to windows running as root.)

Terminal colours are in the .xresources format - you can simply copy the contents into the `~/.Xresources` file if the terminal you use happens to use that file for its config. If yours doesn't (mine doesn't - I use the Xfce terminal), you can use [terminal.sexy](https://terminal.sexy/) to convert the colours to your chosen format.

## Licence
As with the original Arc theme, GPL 3.

## Special thanks
To [the original designer/developer of the Arc theme](https://github.com/horst3180/arc-theme), [the current maintainer](https://github.com/jnsh/arc-theme), and all the contributors throughout the theme's history, for the wonderful work you've done.

To the folks behind [Themix/Oomox](https://github.com/themix-project/oomox), for making many a themer's endeavours easier.

Last but not least, though this may sound weird, to one particular themer: [addy-dclxvi on GitHub](https://github.com/addy-dclxvi/gtk-theme-collections), my gateway to this whole thing.
