
Debian
====================
This directory contains files used to package xbitd/xbit-qt
for Debian-based Linux systems. If you compile xbitd/xbit-qt yourself, there are some useful files here.

## xbit: URI support ##


xbit-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install xbit-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your xbitqt binary to `/usr/bin`
and the `../../share/pixmaps/xbit128.png` to `/usr/share/pixmaps`

xbit-qt.protocol (KDE)

