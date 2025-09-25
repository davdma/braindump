# Git

## Basic Commands
- `git init` - Initialize a new repository
- `git add .` - Stage all changes
- `git commit -m "message"` - Commit changes with message
- `git push origin main` - Push to remote repository
- `git pull` - Pull latest changes from remote
- `git status` - Check current status
- `git log --oneline` - View commit history

## Branching
- `git branch` - List branches
- `git checkout -b feature-branch` - Create and switch to new branch
- `git merge feature-branch` - Merge branch into current branch
- `git branch -d feature-branch` - Delete branch

## Common Workflows
1. Feature branch workflow
2. GitFlow workflow
3. GitHub Flow

## Troubleshooting
- `git reset --hard HEAD` - Reset to last commit (destructive!)
- `git stash` - Temporarily save changes
- `git stash pop` - Restore stashed changes
- `git cherry-pick <commit-hash>` - Apply specific commit

## Best Practices
- Write clear commit messages
- Use conventional commits format
- Keep commits small and focused
- Review changes before committing
- Use .gitignore for unnecessary files
