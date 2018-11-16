
Debian
====================
This directory contains files used to package Dashlited/Dashlite-qt
for Debian-based Linux systems. If you compile Dashlited/Dashlite-qt yourself, there are some useful files here.

## Dashlite: URI support ##


Dashlite-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install Dashlite-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your Dashliteqt binary to `/usr/bin`
and the `../../share/pixmaps/Dashlite128.png` to `/usr/share/pixmaps`

Dashlite-qt.protocol (KDE)

