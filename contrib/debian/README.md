
Debian
====================
This directory contains files used to package darald/daral-qt
for Debian-based Linux systems. If you compile darald/daral-qt yourself, there are some useful files here.

## daral: URI support ##


daral-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install daral-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your daralqt binary to `/usr/bin`
and the `../../share/pixmaps/daral128.png` to `/usr/share/pixmaps`

daral-qt.protocol (KDE)

