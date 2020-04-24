# ts3client-installer
Build .deb package to install latest TeamSpeak3 client for debian.

# Installation
Either build or download the .deb package.
### Build .deb package (recommended)
Build the ts3client.deb package:
```sh
$ git clone https://github.com/PSandro/ts3client-installer.git
$ cd ts3client-installer
$ ./build.sh
```
### Download .deb package
```sh
$ wget https://github.com/PSandro/ts3client-installer/releases/download/v1.0/ts3client.deb
```

### Install .deb package
Install ts3client.deb:
```sh
$ sudo dpkg -i ts3client.deb
```
