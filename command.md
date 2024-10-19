# Git Commands for DevOps

```bash
# Create a new directory
mkdir gitfordevops

# Verify current user
whoami

# Change directory to gitfordevops
cd gitfordevops

# Print working directory
pwd

# Initialize a new Git repository
git init

# Clear terminal screen
clear

# Create and edit a new text file
vim hellodosto.txt

# List files in the directory
ls

# List all files, including hidden files
ls -a

# Check the status of the Git repository
git status

# Create new files
touch nibba.txt nibbi.txt

# Add files to the Git index
git add nibbi.txt
git add nibba.txt

# Remove a file from the index but keep it locally
git rm --cached nibba.txt

# Add the file back to the index
git add nibba.txt

# Commit the changes with a message
git commit -m "adding nibba nibbi"

# Remove a file
rm nibbi.txt

# Restore a deleted file
git restore nibbi.txt

# Edit a file
vim nibbi.txt

# Commit the changes
git commit -m "New modified version"
git commit nibbi.txt -m "new modification"

# Set global Git configuration for user
git config --global user.name "ubuntu"
git config --global user.email "ubuntu@ip-172-31-18-84.us-west-2.compute.internal"

# Add and commit additional files
git add hellodosto.txt
git commit -m "New modified"

# View Git log history
git log

# Create and switch to a new branch
git checkout -b dev

# Switch branches
git switch dev
git switch master

# Create another file
touch nibbu.txt

# View all branches
git branch

# View log history in a one-line format
git log --oneline

# Switch back to the master branch
git checkout master
