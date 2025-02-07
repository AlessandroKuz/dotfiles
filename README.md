# dotfiles
A simple collection of all my dotfiles for linux

## Commands and utils to explore
[ ] fzf
[ ] tmux
[ ] nvim

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

### All packages
#### pacman
```
pacman -S git
```
#### apt / apt-get
```
apt-get install git
apt-get install stow
apt-get install zsh
curl -fsSL https://raw.githubusercontent.com/zimfw/install/master/install.zsh | zsh
apt-get install btop
apt-get install tmux
apt-get install zoxide
add-apt-repository ppa:neovim-ppa/stable
apt-get update && sudo apt-get upgrade
apt-get install neovim
git clone https://github.com/tmux-plugins/tpm ~/.tmux/plugins/tpm
```
#### base
```
cd ~
git clone https://github.com/AlessandroKuz/dotfiles
cd dotfiles
stow zsh
stow tmux
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

## Useful Shortcuts
### tmux
Prefix command shortcuts
- `C-j` and `C-f` for the prefix
- `prefix + c` for new window
- `prefix + n` for next window
- `prefix + p` for previous window
- `prefix + %` or `prefix + v` for new vertical pane (vertical split)
- `prefix + "` or `prefix + h` for new horizontal pane (horizonatl split)
- `prefix + arrow_keys` to move between panes
- `prefix + d` to detach
- `prefix + z` to toggle zooming in and out of the selected pane

Terminal commands for tmux
- `tmux attach` or `tmux a` to attach to latest session, add `-t session` to attach to a specific session
- `tmux list-sessions` or `tmux ls` to list all active sessions

Switching
- Alt+arrow_keys or Alt+vim_keys to switch between panes without using the prefix
- Shift+arrow_keys to switch between windows without using the prefix

Synchronization mode
- `prefix + y` to toggle simultaneous editing of all panes at once

### fzf
- `C-t` opens fzf
- `C-r` opens shell command history in fzf

## Essential packages
- neovim / nvim
- tmux
- fzf
- zoxide

