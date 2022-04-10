# GIT Functions
---
### 1. VERSION

This function checks the version of git

Syntax:

    git --version

### 2. CONFIG

This function sets the name and email of the user

Syntax:

    git config --global user.name 'name'
    git config --global user.email 'email'

### 3. INIT

This function initializes a repository in the current directory

Syntax:

    git init [name]

### 4. ADD

This function adds files to the staging area

Syntax:

    git add [file name]
    git add *.[file type] #adds all files of the given type
    git add . #adds all files to the staging area

### 5. RM

This function removes the said file from the staging area

Syntax:

    git rm --cached [file name]

### 6. STATUS

This function checks the file status, ie. files to e committed, files modified, etc.

Syntax:

    git status

### 7. COMMIT

This function is used to record the code in the version history

    git commit -m "commit message"

### 8. BRANCH

This function lists all branches in the current repository

Syntax:

    git branch

It is also used to create a new branch

Syntax:

    git branch [branchname]

### 9. MERGE

This function merges the specified branch history into the current branch

Syntax:

    git merge [branchname]

### 10. REMOTE

This function is used to connect the local repository to the remote server

Syntax:

    git remote add [var name] [remote server link]

### 11. PUSH

This function is used to send committed changes of master branch/branch commits/pushes all branches to the remote repository

Syntax:

    git push [var name] master
    git push [var name] branch
    git push -all [var name]

### 12. CLONE

This function clones an existing repository using its link from the remote server

Syntax:

    git clone [link]

### 13, PULL

This function fetches and merges changes on remote server to the working directory

Syntax:

    git pull [link]
