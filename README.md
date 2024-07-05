# Git and Terminal Commands Reference

This document provides a quick reference for common Git and terminal commands.

### 1. **`ls -la`**
Lists all files and directories in the current directory in long format, including hidden files (those starting with a dot `.`).

### 2. **`cd ~`**
Changes the current directory to the user's home directory.

### 3. **`mkdir .ssh`**
Creates a new directory named `.ssh` in the current directory. This is typically used to store SSH keys.

### 4. **`ssh-keygen`**
Generates a new SSH key pair for secure communication with remote servers.

### 5. **`git status`**
Displays the state of the working directory and staging area. It shows which changes have been staged, which haven't, and which files aren't being tracked by Git.

### 6. **`git add .`**
Stages all changes in the current directory for the next commit.

### 7. **`git commit -m "YOUR COMMIT MESSAGE"`**
Records the staged changes in the repository with a descriptive message.

### 8. **`git fetch`**
Downloads objects and refs from another repository. It updates the remote tracking branches.

### 9. **`git pull origin BRANCH-NAME`**
Fetches from and integrates with another repository or a local branch. This command is a combination of `git fetch` and `git merge`.

### 10. **`git branch -vv`**
Lists all local branches and shows tracking branches and their statuses.

### 11. **`git checkout BRANCH_NAME`**
Switches to the specified branch and updates the working directory.

### 12. **`clear`**
Clears the terminal screen.

### 13. **`git log`**
Shows the commit history for the repository.

### 14. **`git rebase -i HEAD~2`**
Initiates an interactive rebase for the last two commits. This allows you to edit, combine, or reorder commits.

### 15. **`git rebase --abort`**
Aborts the rebase process and returns the branch to its original state.

### 16. **`git rebase origin BRANCH_NAME`**
Rebases the current branch onto the specified branch from the remote repository.

### 17. **`git rebase --continue`**
Continues the rebase process after resolving conflicts.

### 18. **`git rebase -i HEAD~1`**
Initiates an interactive rebase for the last commit.

### 19. **`git push origin -f BRANCH_NAME`**
Forcibly pushes the current branch to the remote repository, overwriting any changes there. Use with caution.

### 20. **`git rebase -i HEAD~3`**
Initiates an interactive rebase for the last three commits.

### 21. **`history`**
Displays the command history.

### 22. **`history > git-commands.txt`**
Saves the command history to a file named `git-commands.txt`.
