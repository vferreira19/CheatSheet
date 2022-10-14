# clone a remote repository
git clone [url]

# Switch your HEAD to branch
git checkout [branch]

# Create a new branch based on your current HEAD
git branch [new-branch]

# Delete a local branch
git branch -d [branch]

# List all new or modified files - showing which are to staged to be commited and which are not 
git status

# View changes between staged files and unstaged changes in files
git diff

# Add all current changes to the next commit
git add [file]

# Remove a file from the next commit
git rm [file]

# Commit all local changes in tracked  files
git commit –a
git commit -am "An inline  commit message"

# Download all remote changes and merge them locally
git pull [remote] [branch]

# Publish local changes to a remote 
git push [remote] [branch]