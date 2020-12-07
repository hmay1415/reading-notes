##### Reading notes from [Git Intro](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/)

#####
- VCS = version control system
- Local VCS = one database on hard disk that stores changes to files
- Centralized VCS (CVCS) - single server storing all changes
- Distributed VCS (DVCS) - addresses major vulnerability  of CVS - the server as single point of failure. Clients create mirrored repos
- Git is a DVCS taht stores data in file system made up of snapshots. Relies on local operations - history resides on local disk
- Git tracks changes and detects file corruption and makes it hard to lose data
- File states: committed (stored in local database), modified (changed but not committed to database), staged (flagged a changed version to be committed in next snapshot
- Git originated in Linux kernel project - used to use Bitkeeper 

Git Setup Commands:

