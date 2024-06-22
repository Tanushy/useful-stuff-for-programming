# Git Cheat Sheet

## Configuration
- **Set your name**: `git config --global user.name "Your Name"`
- **Set your email**: `git config --global user.email "you@example.com"`
- **Check configuration**: `git config --list`

## Creating Repositories
- **Initialize a new repository**: `git init`
- **Clone an existing repository**: `git clone <repository_url>`

## Basic Snapshotting
- **Check the status of your files**: `git status`
- **Track a new file**: `git add <file>`
- **Stage all changes**: `git add .`
- **Commit staged changes**: `git commit -m "Commit message"`
- **Amend the last commit**: `git commit --amend`

## Branching & Merging
- **List branches**: `git branch`
- **Create a new branch**: `git branch <branch_name>`
- **Switch to a branch**: `git checkout <branch_name>`
- **Create and switch to a new branch**: `git checkout -b <branch_name>`
- **Merge a branch into the current branch**: `git merge <branch_name>`
- **Delete a branch**: `git branch -d <branch_name>`
- **Delete a remote branch**: `git push origin --delete <branch_name>`

## Remote Repositories
- **Add a remote repository**: `git remote add origin <repository_url>`
- **View remote URLs**: `git remote -v`
- **Fetch from remote**: `git fetch`
- **Push changes to remote**: `git push`
- **Pull changes from remote**: `git pull`
- **Push to a specific branch**: `git push origin <branch_name>`

## Inspection & Comparison
- **View commit history**: `git log`
- **View commit history with diffs**: `git log -p`
- **Show changes**: `git diff`
- **Show changes for a specific file**: `git diff <file>`
- **View a specific commit**: `git show <commit_hash>`
- **View changes staged for the next commit**: `git diff --staged`

## Undoing Changes
- **Unstage a file**: `git reset <file>`
- **Undo all changes in working directory**: `git reset --hard`
- **Revert a commit**: `git revert <commit_hash>`
- **Revert to a specific commit**: `git reset --hard <commit_hash>`
- **Remove untracked files**: `git clean -f`
- **Remove untracked files and directories**: `git clean -fd`

## Stashing
- **Stash changes**: `git stash`
- **List stashes**: `git stash list`
- **Apply the latest stash**: `git stash apply`
- **Apply a specific stash**: `git stash apply stash@{n}`
- **Pop the latest stash**: `git stash pop`
- **Drop a specific stash**: `git stash drop stash@{n}`

## Tagging
- **Create a tag**: `git tag <tag_name>`
- **Create an annotated tag**: `git tag -a <tag_name> -m "Tag message"`
- **List tags**: `git tag`
- **Show tag details**: `git show <tag_name>`
- **Push tags to remote**: `git push origin <tag_name>`
- **Push all tags to remote**: `git push origin --tags`
- **Delete a tag**: `git tag -d <tag_name>`
- **Delete a remote tag**: `git push origin :refs/tags/<tag_name>`

## Submodules
- **Add a submodule**: `git submodule add <repository_url> <path>`
- **Initialize submodules**: `git submodule init`
- **Update submodules**: `git submodule update`

## Aliases
- **Create an alias**: `git config --global alias.<alias_name> "<git_command>"`
- **Example**: `git config --global alias.co "checkout"`

This cheat sheet covers many of the most commonly used Git commands. For more advanced usage, refer to the official [Git documentation](https://git-scm.com/doc).
