# Contractor file for elementary OS to install .deb packages 

## Installation

Type commands below in your terminal to download and copy`debinstall.contract` file to Contractor directories.

For current user only:
```sh
wget https://github.com/Romchec/contractor-deb-install/blob/4f1d2883597301072b646e63bccd9055c3d00f69/debinstall.contract && mv ./debinstall.contract ~/.local/share/contractor/
```
For all users(don't forget to give permission to move file to root directory):
```sh
wget https://github.com/Romchec/contractor-deb-install/blob/4f1d2883597301072b646e63bccd9055c3d00f69/debinstall.contract && sudo mv ./debinstall.contract /usr/share/contractor/
```

After that relogin to your user and try it.

## Usage

Click on .deb file with right-mouse button and click "Install package". It will ask for your password, then open terminal with APT package manager, which will tell you about package, show you dependencies and ask you to confirm installation.
