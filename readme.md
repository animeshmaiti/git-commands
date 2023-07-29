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
1. now the project is pushed to the github repository
1. now create a new branch on the github repository
1. now run the following commands on the local machine
```sh
git checkout -b new-branch
git add .
git commit -m "new branch commit"
git push origin new-branch
```
1. you can check the repository url by running the following command
```sh
git remote -v
```
1.you can clone the repository by running the following command
```sh 
git clone git@github.com:animeshmaiti/git-push-commands.git
```
1. you can pull the repository by running the following command
```sh
git pull origin master
```
note: the origin is the remote repository name and master is the branch name
1. switch the branch by running the following command
```sh
git checkout new-branch
```