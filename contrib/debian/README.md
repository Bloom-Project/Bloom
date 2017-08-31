
Debian
====================
This directory contains files used to package BLMd/BLM-qt
for Debian-based Linux systems. If you compile BLMd/BLM-qt yourself, there are some useful files here.

## BLM: URI support ##


BLM-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install BLM-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your BLMqt binary to `/usr/bin`
and the `../../share/pixmaps/BLM128.png` to `/usr/share/pixmaps`

BLM-qt.protocol (KDE)

