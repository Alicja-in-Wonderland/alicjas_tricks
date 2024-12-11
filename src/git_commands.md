# Git Commands Reference Guide

## Basic Commands

### Cloning a Repository
```bash
git clone <repository-url>
```

### Branch Management
- Create a new branch:
  ```bash
  git branch <branch-name>    # Full command
  gb <branch-name>           # Shorthand
  ```
- Switch to a branch:
  ```bash
  git checkout <branch-name>  # Full command
  gco <branch-name>          # Shorthand
  ```

### Pushing Changes
```bash
git push origin <branch-name>
```
Pushes commits from your local branch to the remote repository on GitHub.

## Complete Workflow

### 1. Create a New Branch
```bash
gb <branch-name>
```

### 2. Switch to New Branch
```bash
gco <branch-name>
```

### 3. Stage Files for Commit
```bash
git add .
```
Stages all modified files in the current directory.

### 4. Commit Changes
```bash
gca
```
Creates a commit with the staged changes.

### 5. Push to Remote
```bash
git push origin <branch-name>
```

### 6. Create Pull Request
- Navigate to GitHub.com
- Create a new pull request from your branch

### 7. Merge Pull Request
- Review and merge the pull request on GitHub.com

### 8. Update Local Repository
```bash
gco master                  # Switch to master branch
git pull origin master      # Update local master with remote changes
```

## Tips
- Always ensure you're on the correct branch before making changes!!!
- Use meaningful commit messages to describe your changes and meaningful branch names - 'new-functionality' is NOT very useful.
- Review your changes before pushing to remote