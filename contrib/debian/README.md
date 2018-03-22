
Debian
====================
This directory contains files used to package bulletd/bullet-qt
for Debian-based Linux systems. If you compile bulletd/bullet-qt yourself, there are some useful files here.

## bullet: URI support ##


bullet-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install bullet-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your bullet-qt binary to `/usr/bin`
and the `../../share/pixmaps/bullet128.png` to `/usr/share/pixmaps`

bullet-qt.protocol (KDE)

