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

## Useful Shortcuts
### tmux
Prefix command shortcuts
- `C-j` and `C-f` for the prefix
- `prefix + c` for new window
- `prefix + n` for next window
- `prefix + p` for previous window
- `prefix + "` or `prefix + v` for new vertical pane (vertical split)
- `prefix + %` or `prefix + h` for new horizontal pane (horizonatl split)
- `prefix + arrow_keys` to move between panes
- `prefix + d` to detach

Terminal commands for tmux
- `tmux attach` or `tmux a` to attach to latest session, add `-t session` to attach to a specific session
- `tmux list-sessions` or `tmux ls` to list all active sessions

Switching
- Alt+arrow_keys to switch between panes without using the prefix
- Shift+arrow_keys to switch between windows without using the prefix

