# GIT BASH COMMAND

## CLONE FORKED REPOSITORY FROM GITHUB TO LOCAL

1. Go to local, new directory that would like to clone from git hub
2. git clone https://github.com/shamming/New_Fork_Directory
3. goto the newly created folder that have the copy of forked repository
4. git remote -v


## COMMIT (repo) & PUSH CHANGES

* change working directory

* check status, see whether there's any new files to commit

git status

* stage and add files for commiting

git add .

git status

* commit files

git commit -m "put message here"

git status

* to remove a file from commit

git rm "filename"

* check log if commit is there

git log

* push from repo to github

git push origin master

## CREATE NEW FILE AND PUSH TO GITHUB

1. create new file
2. git init
3. git add .
4. git commit -m "add comment here"
5. git remote add origin URL
6. git push -u origin master

optional: git pull origin master - to ensure sync files from github to repo
