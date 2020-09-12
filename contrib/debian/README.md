
Debian
====================
This directory contains files used to package pivxcoind/pivxcoin-qt
for Debian-based Linux systems. If you compile pivxcoind/pivxcoin-qt yourself, there are some useful files here.

## pivxcoin: URI support ##


pivxcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install pivxcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your pivxcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/pivxcoin128.png` to `/usr/share/pixmaps`

pivxcoin-qt.protocol (KDE)

