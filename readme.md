### Initial setup and push the project to the github repository
1. create a new empty repository on the github
1. create a new project on the local machine
1. open the `terminal` or `git bash` in the project folder and run the following commands
```sh
git init
git remote add origin git@github.com:animeshmaiti/git-push-commands.git
git branch -M master
git add .
git commit -m "first commit"
git push -u origin master
```
### Want to create a new branch and push the project to the github repository
1. now the project is pushed to the github repository
1. now create a new branch on the github repository
1. now run the following commands on the local machine
```sh
git checkout -b new-branch
git add .
git commit -m "new branch commit"
git push origin new-branch
```
### Repository Url
- you can check the current workspace repository url by running the following command
```sh
git remote -v
```
### Clone the existing repository
- you can clone the repository by running the following command
```sh 
git clone git@github.com:animeshmaiti/git-push-commands.git
```
### Pull the existing repository
- you can pull the repository by running the following command
```sh
git pull origin master
```
note: the origin is the remote repository name and master is the branch name
### Switch the branch
- switch the branch by running the following command
```sh
git checkout new-branch
```
### Merge the branch
- merge the branch by running the following command
```sh
git merge new-branch
```
### Delete the branch
- delete the branch by running the following command
```sh
git branch -d new-branch
```
### Delete the branch from the remote repository
- delete the branch from the remote repository by running the following command
```sh
git push origin --delete new-branch
```
### List the branches
- list the branches by running the following command
```sh
git branch
```
### List the branches with the remote repository
- list the branches with the remote repository by running the following command
```sh
git branch -r
```
### List the branches with the remote repository and local repository
- list the branches with the remote repository and local repository by running the following command
```sh
git branch -a
```
### List the branches with the remote repository and local repository with the commit message
- list the branches with the remote repository and local repository with the commit message by running the following command
```sh
git log --oneline --decorate --graph --all
```
### Show the commit message
- show the commit message by running the following command
```sh
git show <commit-id>
``` 
### show commit history
- show commit history by running the following command
```sh
git log
```
### show commit history with the commit message
- show commit history with the commit message by running the following command
```sh
git log --oneline
```
### show commit history with the commit message and the author
- show commit history with the commit message and the author by running the following command
```sh
git log --oneline --author="animeshmaiti"
```
### show commit history with the commit message and the author and the date
- show commit history with the commit message and the author and the date by running the following command
```sh
git log --oneline --author="animeshmaiti" --since="2021-01-01"
```
### generate patch file
- generate patch file by running the following command
```sh
git format-patch -1 <commit-id>
```
### for single commit
- for single commit by running the following command
```sh
git format-patch -1 HEAD
```
### for multiple commit
- for multiple commit by running the following command
```sh
git format-patch -n --stdout > multi_commit.patch
```
