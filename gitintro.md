##### Reading notes from [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

Definitions and History

- VCS = version control system
- Local VCS = one database on hard disk that stores changes to files
- Centralized VCS (CVCS) - single server storing all changes
- Distributed VCS (DVCS) - addresses major vulnerability  of CVS - the server as single point of failure. Clients create mirrored repos
- Git is a DVCS taht stores data in file system made up of snapshots. Relies on local operations - history resides on local disk
- Git tracks changes and detects file corruption and makes it hard to lose data
- File states: committed (stored in local database), modified (changed but not committed to database), staged (flagged a changed version to be committed in next snapshot
- Git originated in Linux kernel project - used to use Bitkeeper 

Git Setup Commands

- git config - allows setting of configuration variables that control aspects of Git's operation and look
- git config --global user.name "NAME" - update identity
- git config --global user.email "EMAIL" - update email
- to check, leave off quoted info 
- if project specific ID, nav to local repo and leave off -global
- git config --list - returns settings
- git help *command* - access manual

To import project or directory into Git:
- cd - change directory
- git init - have created subdirectory named .git

To start tracking repo files:
- git add (star).c
- git add LICENSE
- git commit -m "any message here"

To clone: git clone (url) (insert directory name here if you want to clone into an different directory)

Local Repo Structure:
1 Working Directory - actual files reside here
2 Index - area used for staging
3 Head - points to the most recent commit

File status:
- Tracked files - can be modified, unmodified, or staged - part of most recent file snapshot (cloning repo are tracked)
- Untracked files - not in last snapshot - do not reside in staging area
- git status - command to check status

Tracking and Staging
- git add filename - track one file only 
- git add (star) - track all files in repo
- after using these commands, files are tracked and staged for committing

Committing
- git commit -m "message" - commits changes to HEAD
- git commit -a - commits a snapshot of all changes to tracked files in working directory

Pushing Changes
- git push origin master

Stashing Changes
- git stash - when not ready to commit changes but don't want to lose
- git stash apply - when ready to continue working on changes
- origin - server from whiich you cloned
- master - local branch

Remotes
- git remote - can view short names of all specified remote handles
- git remote -v - can view all remote URLs next to short name






