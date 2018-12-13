
Debian
====================
This directory contains files used to package rtakd/rtak-qt
for Debian-based Linux systems. If you compile rtakd/rtak-qt yourself, there are some useful files here.

## rtak: URI support ##


rtak-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install rtak-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your rtakqt binary to `/usr/bin`
and the `../../share/pixmaps/rtak128.png` to `/usr/share/pixmaps`

rtak-qt.protocol (KDE)

