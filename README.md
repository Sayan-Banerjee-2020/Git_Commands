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

### 12. **`git merge BRANCH-NAME`**
Combines changes from the specified branch into the current branch.

### 13. **`git diff`**
Shows the differences between the working directory, staging area, and the last commit.

### 14. **`git log`**
Displays the commit history for the repository.

### 15. **`git rebase -i HEAD~2`**
Initiates an interactive rebase for the last two commits. This allows you to edit, combine, or reorder commits.

### 16. **`git rebase --abort`**
Aborts the rebase process and returns the branch to its original state.

### 17. **`git rebase origin BRANCH_NAME`**
Rebases the current branch onto the specified branch from the remote repository.

### 18. **`git rebase --continue`**
Continues the rebase process after resolving conflicts.

### 19. **`git push origin -f BRANCH_NAME`**
Forcibly pushes the current branch to the remote repository, overwriting any changes there. Use with caution.

### 20. **`git cherry-pick <commit-hash>`**
Applies the changes introduced by the specified commit to the current branch. Useful for selectively picking commits from one branch and applying them onto another.

### 21. **`git tag TAG-NAME`**
Creates a lightweight tag for the current commit. Tags are often used to mark release points.

### 22. **`git stash`**
Temporarily stores changes that are not ready to be committed, allowing you to switch branches or perform other operations.

### 23. **`git reset HEAD~1`**
Unstages the last commit, keeping the changes in your working directory.

### 24. **`git remote -v`**
Lists all remote repositories associated with the current repository along with their URLs.

### 25. **`git clone REPOSITORY_URL`**
Downloads a copy of the remote repository to your local machine.

### 26. **`git rm FILENAME`**
Removes a file from the Git repository and stages the removal for commit.

### 27. **`git clean -df`**
Removes untracked files from the working directory. The `-d` flag also removes untracked directories, and the `-f` flag forces the operation.

### 28. **`git config --global user.name "Your Name"`**
Sets the global username for Git.

### 29. **`git config --global user.email "your.email@example.com"`**
Sets the global email for Git.

### 30. **`git checkout -b NEW-BRANCH-NAME`**
Creates a new branch and switches to it in one step.

### 31. **`git log --graph --oneline --decorate --all`**
Displays a concise graphical representation of the commit history, showing branches and tags.

### 32. **`git remote add upstream UPSTREAM_REPO_URL`**
Adds a remote repository as an upstream repository. Useful for syncing a forked repository with the original repository.

### 33. **`git show COMMIT-HASH`**
Shows the details of a specific commit, including changes made and metadata.

### 34. **`git grep "search term"`**
Searches the contents of files in the repository for a specified term.

### 35. **`git bisect start`**
Starts a binary search to find the commit that introduced a bug.

### 36. **`git bisect good COMMIT-HASH`**
Marks a specific commit as good during a `git bisect` session.

### 37. **`git bisect bad COMMIT-HASH`**
Marks a specific commit as bad during a `git bisect` session.

### 38. **`git bisect reset`**
Ends the `git bisect` session and returns the repository to its original state.

### 39. **`git reflog`**
Shows a log of all Git actions, including resets, commits, merges, and other operations.

### 40. **`git revert COMMIT-HASH`**
Creates a new commit that undoes the changes introduced by a specific commit.

### 41. **`git submodule update --init --recursive`**
Initializes and updates all Git submodules in the repository, including nested submodules.

### 42. **`git remote set-url origin NEW_REPO_URL`**
Changes the URL of the remote repository named `origin` to a new URL.

### 43. **`git log --author="Author Name"`**
Filters the commit history to show only commits made by a specific author.

### 44. **`git show-branch --all`**
Shows the branches and their commits, highlighting where each branch is merged.

### 45. **`git tag -a TAG-NAME -m "Tag message"`**
Creates an annotated tag with a message for the current commit.

### 46. **`git diff HEAD^ HEAD`**
Shows the changes introduced in the last commit (`HEAD^` refers to the commit before `HEAD`).

### 47. **`git log --since="2 weeks ago"`**
Filters the commit history to show commits made within the last two weeks. Adjust the timeframe as needed.

### 48. **`git blame FILENAME`**
Shows who last modified each line of a file and when.

### 49. **`git reset --hard HEAD`**
Resets the current branch and working directory to match the latest commit. Use with caution as it discards all local changes.

### 50. **`git clean -n`**
Performs a dry run of `git clean`, showing which untracked files would be removed without actually removing them.
