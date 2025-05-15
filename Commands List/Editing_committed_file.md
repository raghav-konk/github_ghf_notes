## So you committed a file and created its snapshot. What if I were to edit that file?

### Right, so file.txt exists now and new lines of text were added to it.

### 1. Lets compare
```
git diff
```
This compares the current file.txt that has been modified and saved in working directory with the one that has been recently committed. It shows
1. If new were added
2. If exisiting lines were deleted/modified

### So, what now?

The files that are modified, they are to be staged once again and and to be committed once again for second snapshot/commit if we want the files to be pushed.

```
git add .
git commit -m "You second commit message"
```