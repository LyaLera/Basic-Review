
# Git Cheat Sheet

## Stage and Snapshot
_git status_ - show modified files in working directory, staged for your next commit     
**git status** - show modified files in working directory, staged for your next commit 
**git add [file]** - add a file as it looks now to your next commit (stage)
1. git reset [file] - unstage a file while retaining the changes in working directory
+ git diff - diff of what is changed but not staged          
`git diff --staged - diff of what is staged but not yet commited`
- [ ] git commit -m “[descriptive message]” - commit your staged content as a new commit snapshot

## BRANCH & MERGE 

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

