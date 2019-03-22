# AIT-Project_Management
Repo for our project.

Wiki
# To be able to use git, you need to download it on your computer .
#Link for windows
Link -> https://git-scm.com/download/win
#Link for macOS
Link -> https://git-scm.com/download/mac

///////////////////////////////////////////////////////////////////

All Git commands listed below.


Getting and creating Projects
# git init  
usage - > Initialize a git Repository
# git clone ssh://git@github.com/[username]/[repository-name].git
usage - > Create a local copy of a remote repository
Basic Snapshotting
# git status
usage - > Check Status
# git add [filename.txt] 
usage - > add a file to the staging area
# git commit - m "[commit message]"
usage - > Mention or Insert a message to your commit . (Output the change that you've made)
# git rm -r [filename.txt]
usage - > Remove a file or folder
# git branch	List branches (the asterisk denotes the current branch)
# git branch -a	List all branches (local and remote)
# git branch [branch name]	Create a new branch
# git branch -d [branch name]	Delete a branch
# git push origin --delete [branchName]	Delete a remote branch
# git checkout -b [branch name]	Create a new branch and switch to it
# git checkout -b [branch name] origin/[branch name]	Clone a remote branch and switch to it
# git checkout [branch name]	Switch to a branch
# git checkout -	Switch to the branch last checked out
# git checkout -- [file-name.txt]	Discard changes to a file
# git merge [branch name]	Merge a branch into the active branch
# git merge [source branch] [target branch]	Merge a branch into a target branch
# git stash	Stash changes in a dirty working directory
# git stash clear	Remove all stashed entries
# git push origin [branch name]	Push a branch to your remote repository
# git push -u origin [branch name]	Push changes to remote repository (and remember the branch)
# git push	Push changes to remote repository (remembered branch)
# git push origin --delete [branch name]	Delete a remote branch
# git pull	Update local repository to the newest commit
# git pull origin [branch name]	Pull changes from remote repository
# git remote add origin ssh://git@github.com/[username]/[repository-name].git	Add a remote repository
# git remote set-url origin ssh://git@github.com/[username]/[repository-name].git	Set a repository's origin branch to SSH
# Inspection & Comparison
# Command	Description
# git log	View changes
# git log --summary	View changes (detailed)
# git diff [source branch] [target branch]	Preview changes before merging
