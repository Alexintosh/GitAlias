# GitAlias
Some handy aliases for git commands

````
gitCommit() {
  git commit -am $1
}
alias ll="ls -alg"
#Undo last commit
alias gundo="git reset --soft HEAD~"
#Make a commit with: gc "My message"
alias gc=gitCommit
alias gs="git status"
alias gd="git diff"
#Push current branch
alias gp="git push origin HEAD"
````

