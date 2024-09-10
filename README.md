## Git
-  Version control system is a tool that helps to track changes in code.
-  Git is a version Control System it is: 
    -popular
    -free and open sourse
    -fast and scalable

- Git is used to track the history, colloborate

## Github
- Website that allows developers to store and manage their code using Git.
- https://github.com
-Repository is a folder where our projects are present

## Configuring Git
<br>
git config --global user.name "My Name" (username of github)
<br>
git config --global user.email "someone@email.com"
<br>
git config --list


## Clone and Status
<br>
Clone - Cloning a repository on our local machine
<br>
git clone <-some link->
<br>
Satus - displays the status of the code
<br>
git status

# to list hidden files
<br> ls-a <br>

## stages in git
<br> untracked - new files that git dosen't yet track <br>
modified - changed<br>
<br> staged- files is ready to commit<br>
<br>unmodified - unchanges<br>

## Add and commit
<br> add -  adds new or changed files in your working directory to the git area <br>
git add <-file name-> <br>
<br>OR git add . - to add all files <br>

<br> commit - it is the record of change <br>
<br> git commit -m "some message"<br>

## Push command
- push - upload local repo content to remote repo 
- command - git push origin main  - here mail is branch name and origin is name of the repo copy -original repo where we had cloned

## Init command
- now if we made repo in local or computer and then we need to add that repo in github then we can use following commands

- init - used to create a new git repo
 <br>git init</br>
 <br>git remote add origin <-link -></br>
 <br>git remote -v     -(to verify remote)</br>
 <br>git branch     -(to check branch)</br>
 <br>git branch -M main    - (to rename branch from master to main)</br>
 <br>git push origin main</br>
 <br> we can use git push -u origin main ---> here flag u stands for upstream (create shortform for the future)


## Workflow
<br>
github Repo --> clone --> changes --> add ---> commit --> push

## Branch command

- git branch (to check branch)
- git branch -M main (to rename branch to main)
- git checkout <-branch name-> (to navigate to other branch)
- git checkout -b <-new branch name -> to create new branch
- git branch -d <-branch name-> -> to delete branch

## Merging code

- way1
<br> git diff <-branch name->  (to compare commits,branches, files and more)
<br> git merge <-branch name->  (to merge 2 branches)

- way2
Create a pr

## PR pull request
- it lets you tell others about changes you have pushed to branch in a repository on github

## PULL command

- git pull origin <-branch name->  ex git pull origin main
- used to fetch and download content from a remote repo and immediately update the local repo to match that content


## Resolving merge conflicts

-  an event that takes place when git is unable to automatically resolve differencein code between two commits.


## Undoing changes
- case 1 : staged changes 
<br> git reset <-file name->
<br> git reset

- case2 : commited changes (for one commit)
<br> git reset HEAD~1   (last commit will be head~1)

- case3: commited changes (for many commits)
<br> git reset <-commit hash->
<br> git reset --hard <-commit hash->

## history of commits
- to check history of commits use git log


## Fork
- a fork is a new repository that shares code and visibility settings with the original 'upstream' repository

- fork is a rough copy