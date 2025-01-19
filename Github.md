# GitHub Cheat Sheet 🚀

## *Basic Git Setup*
bash
# Configure user information
git config --global user.name "Your Name"
git config --global user.email "youremail@example.com"


## *Repository Basics*
bash
# Initialize a Git repository
git init  

# Clone a repository
git clone <repository-url>  

# Add files to staging area
git add <file-name>  
git add .  # Add all files  

# Commit changes
git commit -m "Your commit message"  

# View status
git status  

# View commit history
git log  


## *Branching*
bash
# List branches
git branch  

# Create a new branch
git branch <branch-name>  

# Switch to a branch
git checkout <branch-name>  

# Create and switch to a branch
git checkout -b <branch-name>  

# Merge a branch into the current branch
git merge <branch-name>  

# Delete a branch
git branch -d <branch-name>  


## *Syncing with Remote*
bash
# Add a remote repository
git remote add origin <repository-url>  

# Push changes to remote (default: main branch)
git push origin main  

# Pull changes from remote
git pull origin main  


## *Collaboration*
bash
# Fork a repository (done on GitHub website)

# Sync forked repo with the original
git remote add upstream <original-repo-url>  
git fetch upstream  
git merge upstream/main  

# Create a pull request (done on GitHub website)


## *Stashing Changes*
bash
# Save uncommitted changes
git stash  

# List stashed changes
git stash list  

# Apply stashed changes
git stash apply  

# Drop the stash
git stash drop  


## *Common Commands*
bash
# View differences
git diff  

# Undo last commit (keep changes)
git reset --soft HEAD~1  

# Undo last commit (discard changes)
git reset --hard HEAD~1  

# Remove a file from staging
git reset <file-name>  

# Remove a file from the repository
git rm <file-name>  


## *GitHub Shortcuts*
- *Issues*: Use to track bugs and features.  
- *Pull Requests*: Collaborate and merge changes.  
- *Actions*: Automate workflows (CI/CD).  
- *Projects*: Manage tasks with Kanban-style boards.
