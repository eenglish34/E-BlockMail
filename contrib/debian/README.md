
Debian
====================
This directory contains files used to package bitmoneyd/bitmoney-qt
for Debian-based Linux systems. If you compile bitmoneyd/bitmoney-qt yourself, there are some useful files here.

## bitmoney: URI support ##


bitmoney-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitmoney-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitmoneyqt binary to `/usr/bin`
and the `../../share/pixmaps/bitmoney128.png` to `/usr/share/pixmaps`

bitmoney-qt.protocol (KDE)

