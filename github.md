# Git Tutorial: A Comprehensive Guide
## Version Control
- version control keeps track of the changes you make
    - you can revert back to previous saves
- moved from local to centralized version control, then to distributed to allow for collaboration
- main parts of git
    - snaphot: data saved at a point in time
    - local operations: allows offline work
    - tracking changes: all changes are tracked
    - loss of data: hard for a commit and data to be lost
    - states:
        - committed: saved on local database
        - modified: data changed, but not committed
        - staged: newest version that is captured in the next commit
## History of Git
- allowed for non-linear updates
## Getting Started
- Steps: (for Windows)
    1. Download Git
    2. Git website
    3. GitHub
- Git has a preset graphical user interface, but you can also choose a 3rd party one
- configuration of variables
- identity setting: set up your username and password using the following commands: 
    - git config --global user.name "Username"
    - git config --global user.email "User email"
- can also update default text editor 
- check settings using "git config --list" command
- get help via manual using "git help" command
## Setting up a Git Repository
- importing a project into the directory you would like
- cloning using the "git clone URL" command to download an exising project onto your local computer
## Workflow
- Working directory (acual files are here) ==> Add ==> Index (staging area) ==> Commit ==> Head (most recent commit)
- tracked - part of most recent commit
- untracked - not in the last commit and are not in the staging area
- check status using "git status" command (use filename for specific file, * for all files in a repo)
- add a comment to a commit to summarize what you changed and why
    - "git commit -m "comment" 
    - "git commit -a" to commit all changes
- push updates using "git push origin master" command
- can use "git stash" to hide changes that can be reapplied later
## Remote Repositories
- cloned: origin ==> original server, master ==> local copy
- use "git remote" command to see info for all remote handles
