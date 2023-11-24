# Doom Dotfiles
This repository contains my version of the three Emacs Lisp files that are editable after installing Doom 

# Prerequisites:
- Make Sure you have emacs on your system

``` shell
# Arch:
$ sudo pacman -Syu
$ sudo pacman -S emacs
```

``` shell
# Debian:
$ sudo apt update
$ sudo apt install emacs
```

``` shell
# Fedora:
$ sudo dnf update
$ sudo dnf install emacs
```

- Also Make ure you have the Doom configuration installed:

``` shell
git clone --depth 1 https://doomemacs/doomemacs ~/.config/emacs
~/.config/emacs/bin/doom install
```

# Installation:

``` shell
# remove existing doom config first so git doesnt yell at you for cloning into a non-empty directory
rm -r ~/.config/doom/
git clone https://brohudev/doom-dots.git ~/.config/doom/
~/.config/emacs/bin/doom install
~/.config/emacs/bin/doom sync
```

### Parting Notes:
You should set an alias for the doom binary located at `~/.config/emacs/bin/doom` if you wish to continue using the doom framework (if you haven't already)
