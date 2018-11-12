
Debian
====================
This directory contains files used to package dashgreend/dashgreen-qt
for Debian-based Linux systems. If you compile dashgreend/dashgreen-qt yourself, there are some useful files here.

## dashgreen: URI support ##


dashgreen-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dashgreen-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dashgreenqt binary to `/usr/bin`
and the `../../share/pixmaps/dashgreen128.png` to `/usr/share/pixmaps`

dashgreen-qt.protocol (KDE)

