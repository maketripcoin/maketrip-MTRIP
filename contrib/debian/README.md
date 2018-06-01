
Debian
====================
This directory contains files used to package maketripd/maketrip-qt
for Debian-based Linux systems. If you compile maketripd/maketrip-qt yourself, there are some useful files here.

## maketrip: URI support ##


maketrip-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install maketrip-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your maketripqt binary to `/usr/bin`
and the `../../share/pixmaps/maketrip128.png` to `/usr/share/pixmaps`

maketrip-qt.protocol (KDE)

