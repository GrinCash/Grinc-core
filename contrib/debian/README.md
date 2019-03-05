
Debian
====================
This directory contains files used to package GRINCd/GRINC-qt
for Debian-based Linux systems. If you compile GRINCd/GRINC-qt yourself, there are some useful files here.

## GRINC: URI support ##


GRINC-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install GRINC-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your GRINC-qt binary to `/usr/bin`
and the `../../share/pixmaps/GRINC128.png` to `/usr/share/pixmaps`

GRINC-qt.protocol (KDE)
