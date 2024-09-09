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