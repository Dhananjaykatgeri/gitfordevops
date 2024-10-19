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
git add nibbi.txt nibba.txt

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

....................................

# Git and Bash Commands

## Editing and Viewing Files
- `vim README.md`
- `vim branching.md`
- `cat id_ed25519.pub`
- `cat README.md`

## Directory Navigation
- `cd`
- `cd .ssh`
- `cd github/gitfordevops`

## Listing Files
- `ls`

## Git Commands

### Remote Management
- `git remote -v`
- `git remote set-url origin git@github.com:Dhananjaykatgeri/gitfordevops.git`

### Status Check
- `git status`

### Staging Changes
- `git add README.md`
- `git add branchinh.md`
- `git add branching.md`

### Committing Changes
- `git commit -m "added readme"`
- `git commit -m "added some new changes"`
- `git commit -m "addedd branching strategy"`
- `git commit -m "addeddd branching url"`

### Viewing Log
- `git log`
- `git log --oneline`

### Branching
- `git branch`
- `git checkout -b staging`
- `git checkout -b dev`

### Merging Branches
- `git merge dev`

### Pulling and Pushing
- `git pull origin main`
- `git push`
- `git push origin staging`
- `git push origin dev`

## Key Management
- `sshkeygen`
- `ssh-keygen`

## Miscellaneous
- `clear`
