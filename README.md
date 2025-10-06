# My dotfiles

This repository contains dotfiles for my system running Arch Linux with Hyprland. This is meant for me to backup my dots.

## Requirements

Ensure you have the following packages installed on your system

### Git

```
$ pacman -S git
```

### Github-CLI

```
$ pacman -S github-cli
```

### Stow

```
$ pacman -S stow
```

## ??

May not require Github-CLI. If needed run the following and authenticate your user.

```
$ gh auth login
```

## Installation

First, checkout the dotfiles repo in your $HOME directory using git.

```
$ git clone https://github.com/bitnotfound/dotfiles.git
```

## Additional required packages to complete the setup

```
firefox
nvim
kitty
zsh
ttf-cascadia-code-nerd
fzf
less
zoxide
```

Use GNU Stow to create symlinks

```
$ cd $HOME/dotfiles
$ stow .
```

Reboot your system

## Acknowledgements

 - [Elliott@Dreams of Autonomy](https://www.youtube.com/@dreamsofautonomy)
