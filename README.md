# Working Directory
- Area here all of our files and directories and changes ar living all of the time
- git add : adds the file to the staging area

# Staging Area
- Files and directories that e explicitly add to the staging area
- git commit -m: add the files to the repo

# Git Repo

# Adding multiple fils of a certain type
- git add *.html

# Adding all files in directory (including hidden)
git add -A

# Removing files
it reset HEAD file2.txt

# Ignoring files
create a .gitignore file - line delimited list of file names

# Git Branches
- Listing all branches
     git branch

- Adding a branches
     git checkout -b feature1
 

- Changing branches
    git checkout <branch name>

- Merging a branch
        git merge <branch name>
    So we would switch to master and then merge git merge feature1
- Removing a branch
- Likely shouldn't do this
        git branch -d <branch name>

      /----0----0----0        
     /              /
0----0----0----0----0