The repository contains port of [Hyprland](https://hyprland.org/)
(wayland compositor based on wlroots) for
[Void Linux](https://voidlinux.org).

Tested briefly on a virtual machine (QEMU).

I do not use wayland myself, so you are free to test it as you see fit.

If you encounter any problems and believe the template is to blame,
feel free to open an issue or pull request.

## Installation

Clone this repository and put the `srcpkgs` directory into your local
copy of [void-packages](https://github.com/void-linux/void-packages).

Refer to `xbps-src`'s instructions for building and installing packages
locally.

Follow Void's [documentation](https://docs.voidlinux.org/config/graphical-session/wayland.html)
to set up environment for wayland compositors properly.

Do not forget to follow the [upstream tutorial](https://wiki.hyprland.org/Getting-Started/Master-Tutorial),
too.

## Why not just submit it to void-packages?

See <https://github.com/void-linux/void-packages/issues/37544>.
