## Alright, So the files are are in staginng area and are ready to be committed.

### But before what is a commit?
> Its a snapshot of the contents of the dierctory

Some good practises before writing a commit.
1. As mentioned earlier, a commit is a snapshot of the project.
2. Think of that snapshot as a polaroid photograph, With some empty whitespace below to write some content. This writing provides some context regarding the photo. It could be any thing. Name of the person, place etc.
3. Similary, each commit also need to be followed up by a commit message, that commit message could be anything that provides some context as to why the commit was made. Eg: Bug fix, Adding a new feature, Editing a file to add new content etc.

## So lets commti file.txt with a commit message.

```
 git commit -m "Added the file.txt for indexing purpose"
```
Here:
"Added the file.txt for indexing purpose" - Is the commit message and it is activated by using the option -m after the commit command.