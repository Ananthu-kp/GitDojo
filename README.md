# Git & GitHub Study Guide

# What is Git?
Git is a distributed version control system(VCS) that helps developers track changes in their codes, collaborate with others, and manage projects efficiently.

## Basic Git Commands
## Initialize Git in a folder
git init

## Check the status of files
git status

## Add files to staging area
git add .

## Commit the changes with a message
git commit -m "Initial commit"

## Connect to a remote repository (GitHub)
git remote add origin https://github.com/your-username/repository-name.git

## Push changes to GitHub
git push -u origin main

## Copies an existing repository from GitHub or another remote source
git clone <repo_url>

## Shows the commit history
git log

## Command is used to compare differences between files
git diff
<br>

## Lists all branches in the repository
git branch

## Creates a new branch
git branch <branch_name>

## Switches to a different branch
git checkout <branch_name>

## Alternative to checkout, used for switching branches
git switch <branch_name>

## Deletes a branch
git branch -d <branch_name>

## Retrieves remote changes
git fetch

## Merges the specified branch into the current branch
git merge <branch_name>

## Fetch + Merge
git pull
<br>

## Unstages a file before committing
git reset <file>

## Resets the repository to a previous commit, deleting all changes
git reset --hard <commit_id>

## Creates a new commit that undoes changes from a specific commit
git revert <commit_id>

## Shows a history of all HEAD movements.
git reflog

## Temporarily saves uncommitted changes
git stash

## Restores stashed changes
git stash pop
<br>

## Reapplies commits on top of another branch
git rebase <branch>

## Applies a specific commit from another branch
git cherry-pick <commit_id>

## Creates a tag for a specific commit
git tag <tag_name>

## Displays a simplified commit history graph
git log --oneline --graph




# What is Github?
Github is cloud-based platform(website) that allows developers to store and manage their code using Git.