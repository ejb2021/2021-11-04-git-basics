# 2021-11-05 Git basics

- `git init` : initialize git repositiory in current working directory
- `git status` : give you the status
- `git add : adds file to staging area
- `git commit : creates snapshot and provide message of changes

- `git log : log information
	- `git log --oneine : one line version of log

- `HEAD` : where you currently at
- `git diff HEAD~<NUM> <FILE>` : capares current fie to file <NUM> ago
- `git diff <HASH> <FILE>` : compares file to <HASH> version

- `git checkout <HASH> <FILE>` : restore <FILE> to version in <HASH>
- Use git status to help find commands to unstage and restore file
   - if you run git checkout without the file you can fix this by running `git checkout main`
- git ignore empty folders
- use `.gitkeep` to "keep" an empty folder
- use `.gitignore` to ignore files/patterns

# Remotes 

- `ssh-keygen` : to create ssh keys
- `git remote add <URL> : adds URL
- `git push origin main`: push to the main branch to the origin remote
- `git pull origin main` : pull the main branch from the origin remote
	
