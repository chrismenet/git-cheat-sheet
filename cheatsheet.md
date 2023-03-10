# Git Cheatsheet

## Init a Git

> git init

> git clone 'url'

## Usefull commands

> git status

> git log

## Add and commit

> git add fileName

> git commit -m "my message"

## Branches

> git branch // view all the branches

> git checkout -b features/branchName // create a branch if needed and go to the branch

> git branch features/branchName // create a branch

> git checkout features/branchName // switch to branchName

> git branch -d features/branchName // delete branchName

> git merge features/branchName // merge branchName to current branch

> git push // push current branch to main

# Fetch, Pull & Push

> git fetch // get updates (without the content)

> git pull // fetch + merge -> get updates from the repository

> git push // send updates to the repository

# Pull request

Easiest way: in the portal :)

> gh pr create --base main --head features/1234-new-killing-feature --title '[#1] Initialize repo' --body 'More details on the PR that solves issue #1'

# Addons

## Branch protection

Allow to control reviewers, force pull request ...

## CODEOWNERS file

Define default policy for reviewers

## Issues & pull request templates

Create a .github/ISSUE_TEMPLATE/Bug.md file

# Git flow

## Trunk based development

Work directly on main -> not necessary a good option

## Git flow

Main branch, realease branch & features branches

## GitHub flow

Main branch & features branches -> allow quick deliveries

## Open Source / Inner Source model

- Fork a project (local copy of the project in our repository)
- Update and create a PR
- PR can be done on the original project

