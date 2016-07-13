## LittleOS
Little operating system written from scratch based on:
[littleosbook](https://github.com/littleosbook/littleosbook/)

### System iso
Source: [minit.iso](http://archive.ubuntu.com/ubuntu/dists/xenial/main/installer-i386/current/images/netboot/mini.iso)

### dwm
#### dwm installation

Source: [dwm ubuntu installation guide](https://cannibalcandy.wordpress.com/2012/04/26/installing-and-configuring-dwm-under-ubuntu/)

Packages:

  + build-essential
  + libx11-dev
  + libxinerama-dev
  + sharutils
  + suckless-tools


Installation:

    cd /usr/local/src
    sudo wget http://dl.suckless.org/dwm/dwm-6.0.tar.gz
    sudo tar xvzf dwm-6.0.tar.gz
    chown -R `id -u`:`id -g` dwm-6.0
    cd dwm-6.0
    sudo make clean install
    echo exec dwm >> ~/.xinitrc

#### dwm tutorial

Source: [dwm tutorial](http://dwm.suckless.org/tutorial)

Shortcuts:

  + `Shirt + Alt + Enter` - Terminal


### Packages:
Packages to install:

  + vim
  + git
  + build-essential
  + nasm
  + genisoimage
  + bochs
  + bochs‐sdl

