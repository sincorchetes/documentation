# Calibre

## Introduction
calibre is a powerful and easy to use e-book manager. Users say it’s outstanding and a must-have. It’ll allow you to do nearly everything and it takes things a step beyond normal e-book software.
It’s also completely free and open source and great for both casual users and computer experts. 

 * Save time on managing your e-book collection
 * Use it everywhere and with anything
 * Comprehensive e-book viewer
 * Download news/magazines from the web
 * Share and backup your library easily
 * Edit the books in your collection
 * Satisfy every e-book need and get support

## How to setup
This is the official method to setup Calibre suite, you must get installed this packages first:
 * tar
 * xdg-utils
 * xz
 * sudo
 * wget
 * python3

NOTE: If you do not use `sudo`, you can switch by `su -c "commands"`.
If you don't have this packages you can setup with this command:
```
sudo dnf install -y tar xdg-utils xz wget sudo python3
```  
After, run this official command setup:
```
sudo -v && wget -nv -O- https://download.calibre-ebook.com/linux-installer.sh | sudo sh /dev/stdin
```

## Run calibre
Just only open from your favourite desktop environment, wm, or typing calibre from shell.
