# dotfiles
A simple collection of all my dotfiles for linux

## Requirements

Ensure you have the following installed on your system (Arch Linux commands).

### Git

```
pacman -S git
```

### Stow

```
pacman -S stow
```

## Installation

First, check out the dotfiles repo in your $HOME directory using git

```
$ git clone git@github.com/AlessandroKuz/dotfiles.git
$ cd dotfiles
```

then use GNU stow to create symlinks

```
$ stow .
```
