# git-commands
## Commands to push and pull the code files 
* repo -> repository
* clone -> bring a repo down from the internet (remote repository like Github) to your local machine
* add -> track your files and changes with Git
* commit -> save your changes into Git
* push -> push your changes to your remote repo on Github (or another website)
* pull -> pull changes down from the remote repo to your local machine

# process of uploading code files to github
## Find the verison
* git --version
## set config 
* git config --global user.name "username"
* git config --global user.email xyz@gmail.com
## path of desired code file
* cd "Filepath"
* ls "list of files"
## Initialize repository
* git init
## path to github 
* git remote add origin GITHUBREPO_LINK
* git remote -v
## add new files
* git add . (for all files)
* git add xyz.py (for each file)
* git status
## remove file from staging area
* git reset
* git status
## commit 
* git commit -m "First commit"

## push the code file into github
* git push origin master

# Delete the files from github
* git rm --cached xyz.csv
* git commit -m "Deletes xyz"
* git push origin master




