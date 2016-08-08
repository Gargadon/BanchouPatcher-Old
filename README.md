BanchouPatcher
==============
BanchouPatcher is a xdelta3 GUI for Linux written on Gambas3.

The latest stable version is 2.0.8, codename Muramasa-Dragon.

If you're using Debian/Ubuntu/Mint, please add first my public key:
```
# apt-key adv --keyserver hkp://keyserver.ubuntu.com:80 --recv 7E967DC8
```

Edit your /etc/apt/sources.list and add one of these lines, depending your branch.
```
deb http://www.gargadon.info/apps testing main # For testing (currently Stretch)
deb http://www.gargadon.info/apps unstable main # For unstable (Sid), maybe can work with Ubuntu 16.04
```

and install it with
```
# apt-get update
# apt-get install banchoupatcher
```

If you're using other non-Debian based distributions, you'll need to compile your own package from source.
