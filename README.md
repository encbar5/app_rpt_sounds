## AllstarLink app_rpt Sound Files
This repository simply contains some sound files for use with asterisk and app_rpt, as well as a Debian build directory for creating deb packages.

## Building
In order to build you will need the debian devscripts package installed
```
sudo apt install devscripts
```
Then, to create the deb files, run
```
debuild -uc -us -b
```
