# test
Just learning git yo!

# git tutorial

## Make a copy of a remote reop, to a local source
git clone [https or ssh path]

## Git the difference of remote and local
git diff

## Get the latest from remote branch, based on current branch
git pull

## List the branches, and print the current branch
git branch

## Move to a branch or revert local changes
git checkout [branch name / file name]

## Make new branch from current branch
git branch [new-branch-name]
git checkout [new-branch-name]
git push -u

OR simply...

git checkout -b [new-branch-name]
git push -u

## Your personal stack

### Move the current changes to the top of the stack
git stash

### Make a copy of the top of the stack and place it in your working directory
git stash apply

### Remove the top stack item and place it in the working directory
git stash pop

## Commit your changes
git pull
git status
git add [files and folders to stage commit]
git commit
git push
