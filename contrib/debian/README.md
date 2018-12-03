
Debian
====================
This directory contains files used to package webrubled/webruble-qt
for Debian-based Linux systems. If you compile webrubled/webruble-qt yourself, there are some useful files here.

## webruble: URI support ##


webruble-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install webruble-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your webrubleqt binary to `/usr/bin`
and the `../../share/pixmaps/webruble128.png` to `/usr/share/pixmaps`

webruble-qt.protocol (KDE)

