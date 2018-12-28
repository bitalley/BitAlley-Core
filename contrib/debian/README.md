
Debian
====================
This directory contains files used to package bitalleyd/bitalley-qt
for Debian-based Linux systems. If you compile bitalleyd/bitalley-qt yourself, there are some useful files here.

## bitalley: URI support ##


bitalley-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bitalley-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bitalleyqt binary to `/usr/bin`
and the `../../share/pixmaps/bitalley128.png` to `/usr/share/pixmaps`

bitalley-qt.protocol (KDE)

