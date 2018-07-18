
Debian
====================
This directory contains files used to package dirhamcoind/dirhamcoin-qt
for Debian-based Linux systems. If you compile dirhamcoind/dirhamcoin-qt yourself, there are some useful files here.

## dirhamcoin: URI support ##


dirhamcoin-qt.desktop  (Gnome / Open Desktop)
To install:

	sudo desktop-file-install dirhamcoin-qt.desktop
	sudo update-desktop-database

If you build yourself, you will either need to modify the paths in
the .desktop file or copy or symlink your dirhamcoinqt binary to `/usr/bin`
and the `../../share/pixmaps/dirhamcoin128.png` to `/usr/share/pixmaps`

dirhamcoin-qt.protocol (KDE)

