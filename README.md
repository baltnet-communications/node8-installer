# NodeJS v8.x Installer
This package helps to automate NodeJS v8.x installations. Installing NodeJS using a package manager requires manual configuration of the APT repository list and manually importing the PGP signature key.

It executes same steps as specified in the official [NodeSource setup guide:](https://deb.nodesource.com)
1. Adds appropriate NodeSource debian repository to `/etc/apt/sources.list.d`
2. Inserts NodeSource package signing key as a key ring to `/etc/apt/trusted.gpg.d`

# Installation
Please go to http://pkg.baltnet.net for instructions how to configure Baltnet repository and install this package.
