# Wasta-Vertex Icons (Beta)

**Note:** This is an unfinished beta version. It may not work as expected in some cases.

### Requirements

Since this theme doesn't provide application icons, it needs another icon theme to inherit them.
By default this theme will look for the Moka icon theme (http://mokaproject.com/moka-icon-theme/) to get the missing icons. If Moka is not installed it will use the Gnome icon theme as fallback.
To change the application icons, edit the `index.theme` file and replace `Moka` with the name of your preferred icon theme

For example, if you like the ubuntu-mono-dark icon theme, change

    [Icon Theme]
    Name=Wasta-Vertex
    Inherits=Moka,gnome,hicolor
    Comment=Wasta-Vertex Icon theme

to

    [Icon Theme]
    Name=Wasta-Vertex
    Inherits=ubuntu-mono-dark,gnome,hicolor
    Comment=Wasta-Vertex Icon theme

### Installation

Copy the folder which contains this README to `~/.icons` or to `/usr/share/icons` for system-wide use.

### Bug reporting

If you find a bug, please report it at https://github.com/wasta-linux/wasta-vertex/issues

### Credits

All credits for third party icons used in this theme go to their respective creators:

**Humanity:**  https://launchpad.net/humanity licensed under the terms of the GPL v2

**Vertex:** https://github.com/horst3180/Vertex-icons licensed under the terms of the GPL v3

The remaining icons are created by Rik Shaw and are licensed under the terms of the GPL v3

===
