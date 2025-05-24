# What is a Branch in Git?
Think of a branch as a parallel timeline in your project. You can experiment on a branch without affecting the main project (main or master).

# Create a new branch
```
git branch branch_name
```
# Switch to another branch
```
git switch new-feature
```

# Create and switch in one step
```
git switch -c awesome-idea
```
# List all branches
```
git branch -a
```

# Delete a Branch
```
git branch -d old-branch   # safe delete (only if merged)
git branch -D old-branch   # force delete (even if not merged)
```
