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

## Lemonbar

For information on how to modify Lemonbar and all of the things on it, check out
LemonbarREADME.md
