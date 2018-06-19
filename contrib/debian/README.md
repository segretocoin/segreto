
Debian
====================
This directory contains files used to package segretod/segreto-qt
for Debian-based Linux systems. If you compile segretod/segreto-qt yourself, there are some useful files here.

## segreto: URI support ##


segreto-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install segreto-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your segretoqt binary to `/usr/bin`
and the `../../share/pixmaps/segreto128.png` to `/usr/share/pixmaps`

segreto-qt.protocol (KDE)

