# Hello Github
A small project describing how we work with github

## Adding a file

Explicitly
```console
git add myfile
```
Any file in folder
```console
git add .
```
## Commiting changes
```console
git commit -am 'short message describing what I have changed'
```
## Pushing commits to GitHub
Pushing to master branch
```console
git push origin master
```
## Cloning a repository
```console
git clone https://YOUR_USER_NAME@github.com/peh-empire/hello-github.git
cd hello-github
```
## Add collaborators
To manage access, move to [peh-empire's settings](https://github.com/peh-empire/hello-github/settings), then to `Manage access' and press `Invite a collaborator` and select by `username`
## Create Issue
Move to the repository at `github.com` and file a new Issue. Description shouldbe precise enough to work on task without further communication.
## Create feature branch corresponding to Issue
For an existing Issue, create a **new** local branch like (`-b` switch):
```console
git checkout -b feat/#42
```
Where `#42` is the number of the corresponding Issue.
## Switch branches
To switch to a different *existing* branch:
```console
git checkout branch-name
```
## Push feature branch to server
```console
git push -u origin feat/#42
```
