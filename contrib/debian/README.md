
Debian
====================
This directory contains files used to package valinorcoind/valinorcoin-qt
for Debian-based Linux systems. If you compile valinorcoind/valinorcoin-qt yourself, there are some useful files here.

## valinorcoin: URI support ##


valinorcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install valinorcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your valinorcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/valinorcoin128.png` to `/usr/share/pixmaps`

valinorcoin-qt.protocol (KDE)

