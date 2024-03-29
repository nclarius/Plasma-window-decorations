# Active Accent window decoration

Breeze-based window decoration with or without titlebar that frames the active window in the accent color and the inactive windows in the background color of the current color scheme.

The theme comes in five versions:

- [Frame](https://store.kde.org/p/1678088): Without titlebar, for any color scheme
- [Dawn](https://store.kde.org/p/1709568): With titlebar, for color schemes with light background and dark accent 
- [Light](https://store.kde.org/p/1709554): With titlebar, for color schemes with light background and light accent
- [Dusk](https://store.kde.org/p/1709569): With titlebar, for color schemes with dark background and light accent
- [Dark](https://store.kde.org/p/1709567): With titlebar, for color schemes with dark background and dark accent

![screenshot](.img/screenshot.png)

## Installation

*System Settings* > *Appearance* > *Window Decorations* > *Get New Window Decorations …* > search for ‘Active Accent’  > select your desired flavor > *Install*.

## Issues

If you're having problems, you can try the following:

- Ensure your selected Plasma style follows the color scheme (*System Settings* > *Appearance* > *Plasma Style* > check for *Follows color scheme* and filter by *Color scheme compatible*), else [un-override](https://www.reddit.com/r/kde/comments/rwdgxb/Active_Accent_window_decoration/hre5xlr/) it.
- Ensure you have window borders enabled and set to a normal value (*System Settings* > *Appearance* > *Window Decorations* > *Window border size*).
- If you have or used to have Latte dock, make sure there is no Latte configuration that might affect window borders.
- Clear the Plasma cache (`find ~/.cache -name "*plasma*" -delete`).
- Reset your KWin configuration (delete `~/.config/kwinrc` after backing it up first).
- After making changes to your configuration, restart Plasma and KWin (reboot, or `plasmashell --replace &` and `kwin_x11 --replace &`/`kwin_wayland --replace &`).

Borders on maximized windows unfortunately appears [not to be possible](https://bugs.kde.org/show_bug.cgi?id=451505) for Aurorae decorations.



## Configuration

It is not possible to add configuration options for Aurorae themes, so if you want any changes to the window decorations, you will have to edit the theme yourself. Installed Aurorae themes are located in `~/.local/share/aurorae/themes`. You can edit the configuration file `ActiveAccentXYZrc` to change the width of borders and the style of the titlebar, and the `.svg` files to make modifications on the decoration such as colors and the appearance of buttons. For more information, please refer to [the official documentation](https://develop.kde.org/docs/extend/plasma/aurorae/).


## Small Print

© 2022-2023 Natalie Clarius \<natalie_clarius@yahoo.de\> [nclarius.github.io](https://nclarius.github.io)

The core idea of the implementation is due to [@RealezzZ](https://www.reddit.com/r/kde/comments/ri4zko/comment/howapa9/?utm_source=share&utm_medium=web2x&context=3). The files are based on [Breeze Aurorae](https://store.kde.org/p/1461072/) by [@doncsugar](https://github.com/doncsugar); the credit for most of the work goes to them. The adaption for different styles and packaging is my work.

This work is licensed under the GNU General Public License v3.0.  
This program comes with absolutely no warranty.  
This is free software, and you are welcome to redistribute and/or modify it under certain conditions.  

If you like this project, you can make me happy with a review in the [app store](https://store.kde.org/p/1678088).
