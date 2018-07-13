
Debian
====================
This directory contains files used to package ifpd/ifp-qt
for Debian-based Linux systems. If you compile ifpd/ifp-qt yourself, there are some useful files here.

## ifp: URI support ##


ifp-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install ifp-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your ifpqt binary to `/usr/bin`
and the `../../share/pixmaps/ifp128.png` to `/usr/share/pixmaps`

ifp-qt.protocol (KDE)

