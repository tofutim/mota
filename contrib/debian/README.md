
Debian
====================
This directory contains files used to package motad/mota-qt
for Debian-based Linux systems. If you compile motad/mota-qt yourself, there are some useful files here.

## mota: URI support ##


mota-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install mota-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your motaqt binary to `/usr/bin`
and the `../../share/pixmaps/mota128.png` to `/usr/share/pixmaps`

mota-qt.protocol (KDE)

