#	i3config

This is my custom i3 configuration, based off of electro7's i3 config.

I've made a few changes like removing spanish comments and fixing a few things
so that it defaults to a dark theme, among other things. Feel free to suggest
changes or comment things or steal all of the code or do whatever you want.

Enjoy!

## Prerequisites

- Debian Minimal Install

- Install Required Packages
```
$ apt-get install i3 rxvt-unicode-256color lightdm x11-server-utils
$ apt-get install git vim
$ apt-get install conky curl alsautils
$ apt-get install mdp mpc ncmpcpp
```
- Delete all files in ~/ and clone the repo:
```
$ git clone https://github.com/ttepatti/LinuxConfig.git
```

- Install lemonbar:
```
$ mkdir tmp; cd tmp
$ git clone https://github.com/LemonBoy/bar.git
$ apt-get install build-essential checkinstall
$ apt-get install libxcb1-dev libxcb-xinerama0-dev libxcb-randr0-dev
$ make
$ checkinstall -D make install
```

- Restart computer

## Changing Wallpaper

Changing your wallpaper can be done within lightdm's configuration files.

Run this command:
```
$ sudo vim /etc/lightdm/lightdm-gtk-greeter.conf
```
and look for the line that contains
```
#background=
```
Remove the hash mark to un-comment it and place the path to your image file
after the equals sign. This background will apply to both the lightdm login
screen and the wallpaper after login.

## Lemonbar

For information on how to modify Lemonbar and all of the things on it, check out
LemonbarREADME.md
