# gittest
just for test

[Reference](https://dzone.com/articles/top-20-git-commands-with-examples)
[edureka reference](https://www.edureka.co/blog/git-tutorial/)

> ## Top 20 Git Commands With Examples

Here are the Git commands which are being covered:

**_git config
git init
git clone
git add
git commit
git diff
git reset
git status
git rm
git log
git show
git tag
git branch
git checkout
git merge
git remote
git push
git pull
git stash_**

> ## Git Commands

**_git config_**

Usage: `git config –global user.name “name”`  

Usage: `git config –global user.email “email address”`  

This command sets the author name and email address respectively to be used with your commits.

**_git init_**

Usage: `git init [repository name]` or `git init`

This command is used to start a new repository.

**_git clone_**

Usage: `git clone [url]` 

This command is used to obtain a repository from an existing URL.

**_git add_**

Usage: `git add [file]`

This command adds a file to the staging area.

Usage: `git add *` or  `git add .`

This command adds one or more to the staging area.

**_git commit_**

Usage: `git commit -m “[ Type in the commit message]”`  

This command records or snapshots the file permanently in the version history.

Usage: `git commit -a` 

This command commits any files you’ve added with the git add command and also commits any files you’ve changed since then.

**_git diff_**

Usage: `git diff`  

This command shows the file differences which are not yet staged.

Usage: `git diff –staged` 

This command shows the differences between the files in the staging area and the latest version present.

Usage: `git diff [first branch] [second branch]` 

This command shows the differences between the two branches mentioned.

**_git reset_**

Usage: `git reset [file]`

This command unstages the file, but it preserves the file contents.

Usage: `git reset [commit]`  

This command undoes all the commits after the specified commit and preserves the changes locally.

Usage: `git reset –hard [commit]`

This command discards all history and goes back to the specified commit.

**_git status_**

Usage: `git status` 

This command lists all the files that have to be committed.

**_git rm_**

Usage: `git rm [file]` 

This command deletes the file from your working directory and stages the deletion.

**_git log_**

Usage: `git log` 

This command is used to list the version history for the current branch.

Usage: `git log –follow[file]`  

This command lists version history for a file, including the renaming of files also.

**_git show_**

Usage: `git show [commit]` 

This command shows the metadata and content changes of the specified commit.

**_git tag_**

Usage: `git tag [commitID]`  

This command is used to give tags to the specified commit.

**_git branch_**

Usage: `git branch`  

This command lists all the local branches in the current repository.

Usage: `git branch [branch name]`  

This command creates a new branch.

Usage: `git branch -d [branch name]`  

This command deletes the feature branch.

**_git checkout_**

Usage: `git checkout [branch name]`  

This command is used to switch from one branch to another.

Usage: `git checkout -b [branch name]`  

This command creates a new branch and also switches to it.

**_git merge_**

Usage: `git merge [branch name]`  

This command merges the specified branch’s history into the current branch.

**_git remote_**

Usage: `git remote add [variable name] [Remote Server Link]` 

This command is used to connect your local repository to the remote server.

**_git push_**

Usage: `git push [variable name] master`  

This command sends the committed changes of master branch to your remote repository.

Usage: `git push [variable name] [branch]`  

This command sends the branch commits to your remote repository.

Usage: `git push –all [variable name]`  

This command pushes all branches to your remote repository.

Usage: `git push [variable name] :[branch name]` 

This command deletes a branch on your remote repository.

**_git pull_**

Usage: `git pull [Repository Link]` 

This command fetches and merges changes on the remote server to your working directory.

**_git stash_**

Usage: `git stash save`  

This command temporarily stores all the modified tracked files.

Usage: `git stash pop` 

This command restores the most recently stashed files.

Usage: `git stash list`  

This command lists all stashed changesets.

Usage: `git stash drop`  

This command discards the most recently stashed changeset.