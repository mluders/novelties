# Novelties
Small system tweaks to streamline your development.


# Environment

### Bash history search, partial + up-arrow
Start typing a command, and use the arrow keys to cycle through the commands in your history that start with that prefix.
```bash
# ~/.inputrc

bind '"\e[A": history-search-backward'
bind '"\e[B": history-search-forward'
```

### Git shortcuts
1. Copy `.gitalias.txt` to your home directory
2. Add the following to the bottom of `~/.gitconfig`:
```
[include]
    path = /Users/appfolio/.gitalias.txt
```

### Rails shortcuts
```bash
# ~/.bash_profile

# ...

alias beri='bundle exec ruby -Itest'

#...
```

# Useful programs
| Name        | Description                              | URL                                                                    |
|-------------|------------------------------------------|------------------------------------------------------------------------|
| Menu Meters | Monitor CPU and memory usage on your Mac | [Download](https://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/) |
