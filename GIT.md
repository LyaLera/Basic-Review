
# GIT CHEAT SHEET

## Stage and Snapshot
_git status_ - show modified files in working directory, staged for your next commit     
**git status** - show modified files in working directory, staged for your next commit 
**git add [file]** - add a file as it looks now to your next commit (stage)
1. git reset [file] - unstage a file while retaining the changes in working directory
+ git diff - diff of what is changed but not staged          
`git diff --staged - diff of what is staged but not yet commited`
- [ ] git commit -m “[descriptive message]” - commit your staged content as a new commit snapshot

## Branch & Merge 

Isolating work in branches, changing context, and integrating changes
   
>>>>__git branch__
- list your branches. a * will appear next to the currently active branch
 
>>>>__git branch [_branch-name_]__
- create a new branch at the current commit
   
>>>>__git checkout__
- switch to another branch and check it out into your working directory
   
>>>>__git merge [_branch_]__
- merge the specified branch’s history into the current one
   
>>>>__git log__
- show all commits in the current branch’s history

*****************

# GIT CHEAT SHEET

- **git init**: Initialize a local Git repository.

- **git clone [url]**: Clone a remote Git repository.

- **git add [file]**: Stage changes to a file for commit. Use "git add ." to stage all changes.

- **git commit -m "message"**: Commit staged changes with a message describing the changes.

- **git status:** View the status of your local repository, including any changes that are staged or unstaged.

- **git push:** Push your local changes to a remote repository.

- **git pull:** Pull changes from a remote repository to your local repository.

- **git branch:** List all branches in your local repository. Use "-a" to include remote branches.

- **git checkout [branch]:** Switch to a different branch. Use "-b" to create a new branch.

- **git merge [branch]:** Merge changes from another branch into the current branch.

- **git remote add origin [url]:** Add a remote repository to your local Git repository.

- **git remote -v:** List all remote repositories for your local Git repository.

- **git log:** View the commit history for the current branch.

- **git stash:** Temporarily save changes to a "stash" and revert back to the last commit. Use "git stash apply" to restore the changes later.