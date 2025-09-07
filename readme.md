# Linux & Git Command Cheat Sheet

One command per branch, merged into `main`.

## Commands

### 1) ls
List files and directories.
Example: ls -l

### 2) pwd
Print the current directory path.
Example: pwd

### 3) cd
Change directory.
Examples: cd ..   cd ~/gitlinuxcheat

### 4) mkdir
Create a directory.
Example: mkdir notes

### 5) rm
Remove files or folders.
Examples: rm file.txt   rm -r old-dir

### 6) mv
Move or rename files.
Examples: mv a.txt b.txt   mv a.txt folder/

### 7) cp
Copy files or folders.
Examples: cp a.txt b.txt   cp -r src/ dst/

### 8) cat
Show file contents.
Example: cat readme.md

### 9) grep
Search text in files.
Example: grep -n "main" readme.md
 
### 10) git status
Show changed files and current branch.
Example: git status

### 11) git add
Stage changes for commit.
Examples: git add readme.md   git add .

### 12) git log
View commit history.
Examples: git log --oneline   git log --graph --oneline --decorate

### 13) git commit
Save staged changes with a message.
Example: git commit -m "Update notes"

### 14) git branch
List, create, or delete branches.
Examples: git branch   git branch -d feature

### 15) git merge
Combine another branch into the current branch.
Example: on main run: git merge feature

