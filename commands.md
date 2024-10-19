# Command Line Commands Overview

## Directory and File Management
- **`ls`**: List directory contents.
- **`pwd`**: Print the current working directory.
- **`cd Downloads/`**: Change the directory to Downloads.
- **`mkdir git-for-devops`**: Create a new directory named `git-for-devops`.
- **`cd git-for-devops/`**: Change the directory to `git-for-devops`.
- **`touch nibba.txt`**: Create a new file named `nibba.txt`.
- **`touch nibbi.txt`**: Create another new file named `nibbi.txt`.
- **`ls -a`**: List all files, including hidden files.

## Git Initialization
- **`git init`**: Initialize a new Git repository in the current directory.

## Git Status and Staging
- **`git status`**: Display the status of the working tree.
- **`git add nibba.txt`**: Stage the file `nibba.txt` for commit.
- **`git add nibbi.txt`**: Stage the file `nibbi.txt` for commit.
- **`git rm --cached nibba.txt`**: Unstage the file `nibba.txt`.
- **`git commit -m "Adding Nibba Nibbi"`**: Commit the staged changes with a message.

## Git Configuration
- **`git config --global user.name "PranavSavle"`**: Set the global username for Git.

## Branching and Checkout
- **`git checkout -b dev`**: Create and switch to a new branch named `dev`.
- **`git checkout master`**: Switch back to the `master` branch.
- **`git branch`**: List all branches in the repository.

## Committing Changes
- **`git commit -m "adding nibba nibbi"`**: Commit staged changes with a message.
- **`git add .`**: Stage all changes in the current directory.
- **`git commit -m "nibba changed"`**: Commit the changes with a specified message.

## Viewing Logs and History
- **`git log`**: Show the commit history.
- **`history`**: Display the command history.

## Terminal Management
- **`clear`**: Clear the terminal screen.
