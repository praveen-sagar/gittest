# gittest
just for test

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