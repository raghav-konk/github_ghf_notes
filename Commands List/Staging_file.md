## We have a file called file.txt. How do we get it to the staging phase?
> 1. Initialise the Directory first.
> 2. The file is in untracked state right now.
> 3. Use git add . as follows in the terminal
```
git add .
```
This adds all the files in the the given directory.
> To add that one particular file use *git add <file.txt>*

### How do we check if its successfully staged?
```
git status
```
> This will tell us the status of the repo at any point of time.

## So Far, 
1. We took a file called file.txt.
2. We brought it from working directory to staging directory.
3. We tracked the status of the file.