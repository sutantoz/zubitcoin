
Debian
====================
This directory contains files used to package zubitd/zubit-qt
for Debian-based Linux systems. If you compile zubitd/zubit-qt yourself, there are some useful files here.

## zubit: URI support ##


zubit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install zubit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your zubitqt binary to `/usr/bin`
and the `../../share/pixmaps/zubit128.png` to `/usr/share/pixmaps`

zubit-qt.protocol (KDE)

