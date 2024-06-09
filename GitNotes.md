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

- #### git ignore - tell git not to backup files in .gitignore file created at root directory

- #### git reset - to go back to a particular commit
#### snapshot-complete project information (Each commit is a snapshot)

## Creating a branch
*git branch branch_name*

## Merging 2 branches
*git merge branch_name*
## Merge Conflict
- conflicts between merges of branches. We solve conflicts manually

## cherry-pick
- to pick some particular commits
## To merge a particular commit to  a branch
*git cherry-pick commit_id* 
*git merge branch_name*

## Delete a branch
*git branch -d branchname*

## git fetch
- to fetch changes from server to client to tracking branch
## git merge after fetch
- to update local branch

## git pull
- instead of using both git fetch and git merge


## git rebase
- to manage linear history of branches
*git pull --rebase* - used instead of git fetch + git rebase

## release, the merge
- *git rebase --continue*

## *git push -f*
- force push to delete commits in server and update new commits in local branch.