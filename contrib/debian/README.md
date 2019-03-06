
Debian
====================
This directory contains files used to package ecoreumcoind/ecoreumcoin-qt
for Debian-based Linux systems. If you compile ecoreumcoind/ecoreumcoin-qt yourself, there are some useful files here.

## ecoreumcoin: URI support ##


ecoreumcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ecoreumcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ecoreumcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/ecoreumcoin128.png` to `/usr/share/pixmaps`

ecoreumcoin-qt.protocol (KDE)

