
Debian
====================
This directory contains files used to package testwaged/testwage-qt
for Debian-based Linux systems. If you compile testwaged/testwage-qt yourself, there are some useful files here.

## testwage: URI support ##


testwage-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install testwage-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your testwageqt binary to `/usr/bin`
and the `../../share/pixmaps/testwage128.png` to `/usr/share/pixmaps`

testwage-qt.protocol (KDE)

