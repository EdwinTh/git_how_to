# Git How To

## Accidently starting to develop on master, forgot to create a feature branch.

1) When not added anything yet, just checkout on a new branch:

`git checkout -b newbranch`

And do regular `add` and `commit`

2) When already added, but not yet commited. Add them to the stash:

`git stash`

`git checkout -b`

`git stash pop` 
