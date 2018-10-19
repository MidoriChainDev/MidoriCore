
Debian
====================
This directory contains files used to package midorid/midori-qt
for Debian-based Linux systems. If you compile midorid/midori-qt yourself, there are some useful files here.

## midori: URI support ##


midori-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install midori-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your midoriqt binary to `/usr/bin`
and the `../../share/pixmaps/midori128.png` to `/usr/share/pixmaps`

midori-qt.protocol (KDE)

