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