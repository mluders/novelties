# Novelties
Small system tweaks to streamline your development.


# Environment

1. `Partial History Search`: Start typing a command, and use the arrow keys to cycle through the commands in your history that start with that prefix.
```bash
# ~/.inputrc

bind '"\e[A": history-search-backward'
bind '"\e[B": history-search-forward'
```

# Shortcuts

### Git
```bash
# ~/.bash_profile

alias g="git"
alias ga="git add"
alias gb="git branch"
alias gc="git commit"
alias gd="git diff"
alias gds="git diff --staged"
alias gf="git fetch"
alias gg="git grep"
alias gl="git log"
alias gm="git merge"
alias gco="git checkout"
alias gpl="git pull"
alias gpu="git push"
alias grm="git remote"
alias grb="git rebase"
alias grs="git reset"
alias gs="git status"
alias GS="git status"
alias gsh="git show"
alias gw="git whatchanged"
alias snapshot="git commit -m 'wip'"
alias gcan="git commit --amend --no-edit"
```

### Rails
```bash
# ~/.bash_profile

alias be='bundle exec'
alias beri='be ruby -Itest'
alias brake='bundle exec rake'
alias mg='bundle exec rails db:migrate'
alias mgt='bundle exec rails db:migrate RAILS_ENV=test'
```

### Rubocop
```bash
# ~/.bash_profile

# Rubocop all changed files, starting at a given SHA
alias rubodiff='gd --name-only --relative $1 | xargs rubocop'
```

# Useful programs
| Name        | Description                              | URL                                                                    |
|-------------|------------------------------------------|------------------------------------------------------------------------|
| Menu Meters | Monitor CPU and memory usage on your Mac | [Download](https://member.ipmu.jp/yuji.tachikawa/MenuMetersElCapitan/) |
