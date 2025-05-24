# What is the role of .git-keep?

Alright, say if a new empty folder is made and you tried to stage and commit it.

 This DOES NOT work.

Git usually does not keep a track of empty folders.

### So How do we fix this ?

We create a file called .gitkeep with the same name and no separate extension. just **.gitkeep** and place it in the empty folder that we want to keep tracked.

## Why we do this?

Well first reason to think of is to preserve the folder directory tree structure for future use and what not?
