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

- Ensure your Plasma style follows the color scheme (*System Settings* > *Appearance* > *PLasma Style* > check for *Follows color scheme* and filter by *Color scheme compatible*).
- Ensure you have window borders enabled and set to some medium value (*System Settings* > *Appearance* > *Window Decorations* > *Window border size*).
- Delete everything `plasma` in `~/.cache` (`find ~/.cache - name "*plasma*" -delete`).
- Delete yor `~/.config/kwinrc` (after backing it up first).



## Configuration

The theme will be installed to `~/.local/share/aurorae/themes`. You can edit the configuration file `ActiveAccentXYZrc` to change the width of borders and the style of the titlebar, and the `.svg` files to make modifications on the decoration such as colors and the appearance of buttons. For more information, please refer to the [Aurorae docs](https://techbase.kde.org/User:Mgraesslin/Aurorae).



## Small Print

© 2022 Natalie Clarius \<natalie_clarius@yahoo.de\>

The core idea of the implementation is due to [@RealezzZ](https://www.reddit.com/r/kde/comments/ri4zko/comment/howapa9/?utm_source=share&utm_medium=web2x&context=3) and the files are based on [Breeze Aurorae](https://store.kde.org/p/1461072/). The adaption for different styles and packaging is my work.

This work is licensed under the GNU General Public License v3.0.  
This program comes with absolutely no warranty.  
This is free software, and you are welcome to redistribute and/or modify it under certain conditions.  

If you would like to thank me, you can always make me happy with a review or a cup of coffee:  
<a href="https://store.kde.org/p/1678088"><img src=".img/kdestore.png" height="30"/></a>
<a href="https://www.paypal.com/donate/?hosted_button_id=7LUUJD83BWRM4"><img src="https://www.paypalobjects.com/en_US/DK/i/btn/btn_donateCC_LG.gif" height="30"/></a>&nbsp;&nbsp;<a href="https://www.buymeacoffee.com/nclarius"><img src="https://cdn.buymeacoffee.com/buttons/v2/default-yellow.png" height="30"/></a>
