# ZSH Config

My personal ZSH configuration:

```sh
#allow you to change into a directory just by typing its name and pressing enter, without having to type "cd" first
autoload -Uz chpwd_cd 

COMPLETION_WAITING_DOTS="true"

# ----------------------
# Git Aliases
# ----------------------
alias ga='git add'
alias gaa='git add .'
alias gaaa='git add -A'
alias gc='git commit'
alias gcm='git commit -m'
alias gd='git diff'
alias gi='git init'
alias gl='git log'
alias gp='git pull'
alias gpsh='git push'
alias gss='git status -s'
alias gs='echo ""; echo "*********************************************"; echo -e "   DO NOT FORGET TO PULL BEFORE COMMITTING"; echo "*********************************************"; echo ""; git status'


```
