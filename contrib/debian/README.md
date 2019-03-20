
Debian
====================
This directory contains files used to package alphacupd/alphacup-qt
for Debian-based Linux systems. If you compile alphacupd/alphacup-qt yourself, there are some useful files here.

## alphacup: URI support ##


alphacup-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install alphacup-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your alphacupqt binary to `/usr/bin`
and the `../../share/pixmaps/alphacup128.png` to `/usr/share/pixmaps`

alphacup-qt.protocol (KDE)

