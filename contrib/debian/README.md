
Debian
====================
This directory contains files used to package stablecoind/stablecoin-qt
for Debian-based Linux systems. If you compile stablecoind/stablecoin-qt yourself, there are some useful files here.

## stablecoin: URI support ##


stablecoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install stablecoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your stablecoinqt binary to `/usr/bin`
and the `../../share/pixmaps/stablecoin128.png` to `/usr/share/pixmaps`

stablecoin-qt.protocol (KDE)

