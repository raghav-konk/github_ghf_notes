## Here we will talk about undoing a commit. 
### Note: Not amending it.

## Let's say your recent commit is as follows

```
git commit -m "Modified index.html to include dogs - BIG MISTAKE"
```
This means you made a commit with the above mentioned commit message and this commit has a unique hash. Let's say a123.

### You realised that this was a mistake and thought of reverting this commit.

```
git revert --no-edit HEAD
```
### This creates a new commit, that undoes the previous commit and everything will be the way it was before the previous commit.

## Cons: 
1. This creates an additional commit with its own hash.
2. Keeps the timeline more cluttered and disorganised.

## About HEAD
The head is basically the recent commit in the branch. More on that later.