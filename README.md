# Git Lab
## Basics
- `git config --global user.name "<name>"` - add name to configuration
- `git config --global user.email "<email>"`- add email to configuration
- `git init`: create a repository in the current folder
- `git add <filename>` - adds file to staging area
- `git commit` - commits the file to the master branch, opens message file
   - `git commit -m "message"` - Commits with message
- `git status` - see the status of the files in the repository
- `git log` - check the log file
   - `git log --oneline` - shortened version of log
- `git diff` - shows difference between current state and last known git state
   - `--staged` - used when file is in staging area
   - `HEAD~#` - compares with # of commits previous to HEAD
   - `<hash>` - compares with the commit given by hash
- `HEAD` - where you are currently looking (ie, active files)

## Branches
- `git branch <branchname>` - creates a new branch
- `git branch -a` - list branches
- `git switch <branchname>` - switch to branch
   - `git checkout ...` - for older versions

