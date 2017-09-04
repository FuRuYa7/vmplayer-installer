VMware Installer
This script can download, install, upgrade and remove VMware Workstaton/Player. It supports VMware Workstation Player version 12.x.x 64 bit and VMware Player 6.x.x 32 bit.

Copyright (C) 2014-2017 Paweł Pijanowski

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>.

Dependencies:
-------------
coreutils
grep
gawk
iputils-ping
sparky-remsu
sparky-xterm
wget
yad

Install:
-------------
su (or sudo) 
./install.sh

Uninstall:
-------------
su (or sudo)
./install.sh uninstall