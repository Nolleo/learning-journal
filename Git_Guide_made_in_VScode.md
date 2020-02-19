# Git Guide
[Original link from Udemy](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/#7_1)

1. Version control - record changes, reduce mistakes with file changes
    1. revert 
    1. track 
    1. compare
1. Stages
    1. Modified - changed but not commited
    1. Committed - stored locally
    1. Staged - to be changed in next snapshot [Visual of commit process](https://blog.udemy.com/wp-content/uploads/2015/08/image066.png)

### Customization
- COMMAND: git config
    - --global user.name "Jane Smith"
    - --global user.email "example@email.com"
- confirm conifg: 
    - COMMAND: git config --global user.name (should return Jane Smith)
    - COMMAND: git config --global user.email (should return example@email.com)
- $ git config --list

### Getting help
- git help command
- git command --help
- man git-command

### Importing
A.C.P. - to make changes to GitHub 
 - Add the changes to local repo
 - Commit changes to GitHub "a photo with a message"
 - Push the changes to GitHub

### COMMANDS

cdwr - get back to User
mkdir - make new directory
git clone right-click ***
ls - list
ls -a - list all
code . - open all files in a repo
git status - gets status of origin (local repo) to master (GitHub)
   - MAKE THIS routine to do between git add, git status, git commit
git add <file name>- add the file
git commit -m - makes change and message into commit
   - git commit -m "demo" - makes the message "demo" with the commit
git push origin master - updates the repo *ORIGIN space MASTER
git fetch - went to GitHub from local to make aware of changes
   - git fetch, then git status
git diff origin/master - show difference between files (RED COLOR = difference) ORIGIN slash MASTER
git pull origin master *ORIGIN space MASTER - find conflict
  - git status  - branch should be up to date

### Saving
 - Tacked - part of most recent snapshot, can be modified, unmodified or staged
 - Untracked - NOT in the snapshot, still in staging area
 [Life Cycle of File Image](https://blog.udemy.com/wp-content/uploads/2015/08/image006.png)

