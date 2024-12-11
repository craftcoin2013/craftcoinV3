
Debian
====================
This directory contains files used to package craftcoind/craftcoin-qt
for Debian-based Linux systems. If you compile craftcoind/craftcoin-qt yourself, there are some useful files here.

## craftcoin: URI support ##


craftcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install craftcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your craftcoin-qt binary to `/usr/bin`
and the `../../share/pixmaps/craftcoin128.png` to `/usr/share/pixmaps`

craftcoin-qt.protocol (KDE)

