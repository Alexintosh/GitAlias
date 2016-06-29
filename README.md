# GitAlias
Some handy aliases for git commands

````
#Undo last commit
alias gundo="git reset --soft HEAD~"

#Make a commit with: gm "My message"
alias gm=gitCommit

#Checkout to a new hotfix/{$name} branch
alias gh=gitHotfix

#Git status
alias gs="git status"

#Git Diff
alias gd="git diff"

#Git branch
alias gb="git branch"

#Checkout to a new feature/{$name} branch
alias gf=gitFeature

#Checkout to {branch_name}
alias gc=gitCheckout

#Push current branch
alias gp="git push origin HEAD"


gitCommit() { git commit -am $1 }
gitFeature(){ git checkout -b feature/$1 }
gitHotfix(){ git checkout -b hotfix/$1 }
gitCheckout(){ git checkout $1 }
````
