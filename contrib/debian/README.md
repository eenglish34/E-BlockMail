
Debian
====================
This directory contains files used to package eblockmaild/eblockmail-qt
for Debian-based Linux systems. If you compile eblockmaild/eblockmail-qt yourself, there are some useful files here.

## eblockmail: URI support ##


eblockmail-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install eblockmail-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your eblockmailqt binary to `/usr/bin`
and the `../../share/pixmaps/eblockmail128.png` to `/usr/share/pixmaps`

eblockmail-qt.protocol (KDE)

