# git-bash-alias

Bash shorthand aliases for common git commands to save some keystrokes.

```
alias gs='git status
alias ga='git add .'
alias gp='git push'

#git commit 
alias gc='function _gc(){ git commit -m “$1”; };_gc’


