
Debian
====================
This directory contains files used to package natud/natu-qt
for Debian-based Linux systems. If you compile natud/natu-qt yourself, there are some useful files here.

## natu: URI support ##


natu-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install natu-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your natuqt binary to `/usr/bin`
and the `../../share/pixmaps/natu128.png` to `/usr/share/pixmaps`

natu-qt.protocol (KDE)

