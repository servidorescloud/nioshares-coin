
Debian
====================
This directory contains files used to package niosharesd/nioshares-qt
for Debian-based Linux systems. If you compile niosharesd/nioshares-qt yourself, there are some useful files here.

## nioshares: URI support ##


nioshares-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install nioshares-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your nioshares-qt binary to `/usr/bin`
and the `../../share/pixmaps/nioshares128.png` to `/usr/share/pixmaps`

nioshares-qt.protocol (KDE)

