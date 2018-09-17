# Videk OpenVPN client

Videk OpenVPN client deb package source. This package provides systemd service for vpn connection to the Videk management system.

To build Debian package:

    $ dpkg-buildpackage -b -uc

When built, install the package with:

    $ sudo dpkg -i videk-vpn_1.0.0-1_all.deb

To add a new release in change log:

    $ dch -i

After installation, the videk.ovpn file must be placed in `/etc/videk/` directory.
