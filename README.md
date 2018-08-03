#Git & GitHub for Beginners
Record some common commands for git.
##Creating a Repository
Create a new repository which Git can track changes in:
```shell
$ git init
```
Check the git repository status:
```shell
$ git status
```
##Staging files
We need to add our files to a staging area before we commit them:
```shell
$ git add <file>...
```
We can also use the command below to include all the files to be committed:
```shell
$ git add .
```
Unstage files:
```shell
$ git rm --cached <files>...
```
unstage all files:
```shell
$ git rm -r -cached .
```
##Making Commits
Commit changes:
```shell
$ git commit -m ""
```
Log git commit history:
```shell
$ git log
$ git log --oneline
```
##Undoing Things
Go back and check out one particular commit, but it's read only:
```shell
$ git checkout <commit id>
Return to the master branch:
$ git checkout master
```
Revert one particular commit:
```shell
$ git revert <commit id>
```
Go back to one particular commit and return:
```shell
$ git reset <commit id> --hard
$ git reflog
```