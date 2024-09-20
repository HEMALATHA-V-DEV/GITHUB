# GITHUB

# git init	
Initializes a new git repository in the current directory.	
When starting a new project.

# git clone <repository-url>	
Creates a copy of an existing git repository.	
To download a project from a remote repository.

# git status	
Shows the current status of the repository, including staged, unstaged, and untracked files.	
To check what changes you’ve made.

# git add <file>	
Stages a specific file for commit.	
To include changes in the next commit.

# git add .	
Stages all changes in the current directory.	
To prepare all modified files for the next commit.

# git commit -m "message"	
Commits the staged changes with a descriptive message.	
To save your changes in the repository.

# git log	
Displays the commit history.	
To view past commits and their messages.

# git log --oneline	
Shows a simplified commit history in one line per commit.	
For a quick overview of commit history.

# git diff	
Shows the differences between the working directory and the last commit.	
To review changes before staging.

# git diff --staged	
Shows the differences between the staged changes and the last commit.	
To see what will be committed.

# git branch	
Lists all branches in the repository.	To see the branches available in your project.

# git branch <branch-name>	
Creates a new branch with the specified name.	
To start a new line of development.

# git checkout <branch-name>	
Switches to the specified branch.	
To work on a different branch.

# git checkout -b <branch-name>	
Creates a new branch and switches to it in one command.	
To start a new branch quickly.

# git merge <branch-name>	
Merges changes from the specified branch into the current branch.	
To combine work from different branches.

# git pull	
Fetches changes from a remote repository and merges them into the current branch.	
To update your local branch with remote changes.

# git push	
Sends committed changes from your local repository to a remote repository.	
To share your changes with others.

# git remote add <name> <url>	
Adds a new remote repository with a specified name and URL.	
To link your local repository to a remote one.

# git remote -v	
Lists all remote repositories linked to your local repository.	
To check remote connections.

# git fetch	
Downloads changes from a remote repository without merging them.	
To see changes before integrating them.

# git reset <file>	
Unstages a specific file, keeping changes in the working directory.	
To remove a file from staging.

# git reset --soft HEAD~1	
Undoes the last commit but keeps changes staged.	
To adjust your last commit without losing changes.

# git reset --mixed HEAD~1	
Undoes the last commit and unstages changes.	
To keep changes in the working directory but remove them from staging.

# git reset --hard HEAD~1	
Discards all changes and resets to the last commit.	
With caution, as it will lose all uncommitted changes.

# git stash	
Temporarily saves changes that are not ready to be committed.	
To clear your working directory while keeping your changes.

# git stash pop	
Restores the most recently stashed changes.	
To get back your saved changes after a stash.

# git stash list	
Lists all stashed changes.	
To see what you have temporarily saved.

# git stash apply	
Applies the most recent stash without removing it from the stash list.	
To keep the stash for future use while applying the changes.

# git tag <tag-name>	
Creates a tag for a specific commit, usually to mark a release.	
To label important points in the history.

# git tag -a <tag-name> -m "message"	
Creates an annotated tag with a message.	
To add more information about the tag (e.g., release notes).

# git tag -d <tag-name>	
Deletes a tag from your local repository.	
If a tag is no longer needed or was created by mistake.

# git show <tag-name>	
Displays information about a specific tag, including the commit it points to.	
To review details of a tagged commit.

# git cherry-pick <commit>	
Applies the changes from a specific commit to the current branch.	
To selectively apply changes from one commit to another branch.

# git revert <commit>	
Creates a new commit that undoes the changes from a specific commit.	
To reverse changes while keeping history.

# git config --global user.name "<name>"	
Sets your name for commits globally.	
To identify yourself in commits.

# git config --global user.email "<email>"	
Sets your email for commits globally.	
For commit attribution.

# git config --list	
Displays all git configuration settings.	
To review your current git configuration.

# git help <command>	
Provides help information about a specific git command.	
To get more details on any command.

# git rm <file>	
Removes a file from the working directory and stages the removal for commit.	
To delete files from the repository.

# git mv <old-file> <new-file>	
Renames a file and stages the change.	
To move or rename files within the repository.

# git clean -f	
Removes untracked files from the working directory.	
To clean up files that are not being tracked by Git.

# git clean -fd	
Removes untracked files and directories.	
To clean up both files and directories that are not tracked.

# git archive <branch-name> --output=<file.zip>	
Creates a zip file of the specified branch’s contents.	
To export project files without git metadata.

# git reflog	
Shows a log of all references and movements in the repository.	
To find lost commits or track branch movements.

# git bisect	
Uses binary search to find a commit that introduced a bug.	
For debugging and isolating issues.

# git submodule add <repository-url> <path>	
Adds a submodule to the project.	
To include external repositories within your project.

# git submodule update --init	
Initializes and updates submodules in the project.	
To sync submodules with their repositories.

# git rebase <branch>	
Reapplies commits from the current branch onto the specified branch.	
To integrate changes from one branch into another.

# git rebase -i <commit>	
Starts an interactive rebase to edit, squash, or reorder commits.	
To clean up your commit history.

# git rebase --continue	
Continues the rebase process after resolving conflicts.	
After fixing merge conflicts during a rebase.

# git rebase --abort	
Cancels the rebase process and returns to the state before the rebase began.	
If you encounter too many conflicts and want to start over.

# git log --oneline --decorate --graph	
Displays a visual representation of the commit history with tags and branches.	
To see a compact and informative view of the project's commit history.

# git log <tag-name>	
Shows the commit history up to a specific tag.	
To review changes made before a particular release.
