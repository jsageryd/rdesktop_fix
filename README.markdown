rdesktop fix
============

This is a workaround to have the AppGate java client run rdesktop in fullscreen mode with Swedish keyboard layout on Ubuntu through wrapping the rdesktop binary.

Usage
------------------
1. sudo mv (this directory) /usr/bin/rdesktop_
2. sudo mv /usr/bin/rdesktop /usr/bin/rdesktop_/
3. sudo ln -s /usr/bin/rdesktop_/start.sh /usr/bin/rdesktop

Disclaimer
------------------
I take no responsibility for this should it cause any harm.
