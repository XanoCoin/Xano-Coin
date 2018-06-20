
Debian
====================
This directory contains files used to package Xanod/Xano-qt
for Debian-based Linux systems. If you compile Xanod/Xano-qt yourself, there are some useful files here.

## Xano: URI support ##


Xano-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Xano-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Xanoqt binary to `/usr/bin`
and the `../../share/pixmaps/Xano128.png` to `/usr/share/pixmaps`

Xano-qt.protocol (KDE)

