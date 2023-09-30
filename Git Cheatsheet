# How to Use Git
An Incomplete Guide

Here is an [official cheat sheet](https://education.github.com/git-cheat-sheet-education.pdf).

## Some important terms to know:

**Repository:** Is a central “folder” where git will be saving all the files to and their progress

**Branch:** In a project the main program would be considered the stem and a branch would be a copy of all the files from the stem where you can tinker with the files to edit the project without affecting the main project. A branch can then be merged back into the main project with the merging command.

**Merge:** Will bring a branch back to the main stem with auto merge which essentially will analyze and compare all the files from the branch and main stem and keep the most recently saved file of each (this can be overridden). 

**Pull request:** Make a request to merge your branch into the main branch in the repository. Another person can review the changes made on your branch, give feedback, and then merge your branch into the main one

## Some important git commands:
`git init`
Initializes a git repository

`git status`
Reports status of files that are being un/tracked (any gitignore files will not show)

`ls`
List all items in directory

`git log`
review and read a history of things that changed in the repository in list form

`git clone [url]`
Makes a copy of the repository

`git branch`
lists your branches. a * will appear next to the currently active branch 

`git branch [branch-name]`
creates a new branch with the current commits you’ve made

`git checkout [branch-name]`
switches to another branch and checks it out into your working directory (the files on your computer will match the branch you’re now in)

`git checkout --track [remote]/[branch-name]`
switches to a new branch that tracks an already-existing remote branch

`git merge [branch-name]`
merge specified branch to current branch

`git branch –delete [branch-name]`
deletes the branch (locally)

`git add .`
add all changes in the working directory to the staging area

`git add [file-name]`
add specific edited file in the working directory to the staging area

`git commit -m “comment”`
Saves the changes you’ve made so far to the branch you’re working on. The comment should be a brief description of the changes. If you do not type in the message, the VIM text editor will prompt you to create one.

`git rm --cached [filename]`
Will remove the tracking on the file

`git push`
Sends all the changes you’ve made in the local repository to the remote repository

`git push [remote] [branch name]`
Specifies which branch you are pushing and to which remote (it’s probably origin).

`git push -u [remote] [branch name]`
If you don’t have a remote branch (it’s only on your computer) this creates a remote branch and names it, and pushes your changes to it.

`git pull`
Adds any changes in the remote repository that you don’t have to your local repository (do this before starting to add stuff on your local branch)

`git reset`
Undo local changes / undo uncommitted changes

`git revert`
Undo committed changes

`git remote -v`
Shows what remotes you are linked to

`git remote add upstream [link to upstream repository]`
Adds an upstream that you can fetch from and push to

## Ignore changes
`vim .gitignore`
create a file called .gitignore and insert the name of the file you want to ignore

`git add .gitignore`
add .gitignore file in the working directory to the staging area

`git commit -m “ignore file”`
save your changes to the local repository and add comments

*Example: if a file, testfile, is written in the .gitignore; after we use vim testfile to make changes, the changes are not shown when we use git status.*
