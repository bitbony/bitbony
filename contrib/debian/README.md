
Debian
====================
This directory contains files used to package bitbonyd/bitbony-qt
for Debian-based Linux systems. If you compile bitbonyd/bitbony-qt yourself, there are some useful files here.

## bitbony: URI support ##


bitbony-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitbony-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitbony-qt binary to `/usr/bin`
and the `../../share/pixmaps/bitbony128.png` to `/usr/share/pixmaps`

bitbony-qt.protocol (KDE)

