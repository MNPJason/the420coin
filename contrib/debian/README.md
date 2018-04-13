
Debian
====================
This directory contains files used to package the420coind/the420coin-qt
for Debian-based Linux systems. If you compile the420coind/the420coin-qt yourself, there are some useful files here.

## the420coin: URI support ##


the420coin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install the420coin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your the420coin-qt binary to `/usr/bin`
and the `../../share/pixmaps/the420coin128.png` to `/usr/share/pixmaps`

the420coin-qt.protocol (KDE)

