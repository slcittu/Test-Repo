# Git Notes

## Installation
### For Opensuse Linux
*sudo zypper install git*
### For Windows
*winget install git.git*

## Git Registeration
*git config --global user.name "yourname"*

*git config --global user.email "yourmailid"*

## Initialise a git repository
- Create a folder
- Open that folder in terminal

*git init*

## Check Status of files edited
*git status*

## Check the Git usage and history

*git log* or *git log --all*

## Commit a change
- *git add -all*
- *git commit -m "Message"*

## To rollback to a checkpoint
- *git checkout branch_name/commitId*

## Adding to Github
- Create a repository in github
- Copy the repo link
- In terminal, *git remote add nameforrepo copiedlink*


## Change someone's files
*git pull nameforrepo branch_name*

#### head - points the latest commit

## Add a repo to git
*git remote add hub gitlink*
## Updating the changes to github
*git push nameforrepo branch_name*

## How to update a change in github
*git add --all*

*git commit -m "Message"*

*git push hub master*

