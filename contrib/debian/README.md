
Debian
====================
This directory contains files used to package netchaind/netchain-qt
for Debian-based Linux systems. If you compile netchaind/netchain-qt yourself, there are some useful files here.

## netchain: URI support ##


netchain-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install netchain-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your netchainqt binary to `/usr/bin`
and the `../../share/pixmaps/netchain128.png` to `/usr/share/pixmaps`

netchain-qt.protocol (KDE)

