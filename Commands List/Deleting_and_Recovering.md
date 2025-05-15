# Okay, recovering a deleted  file happens in multiple ways. Its important to know what situation applies to us.

### Right Each situation is explained in three points followed by solution and a brief explanation.


# Scenario-1
>### 1. You made a commit of a file, say *index.html*
>### 2. After the commit was made, the file has been removed
>### 3. Now the file is no longer with you in your working directory

# Solution for Scenario-1

### Since a version of this file exists as commit in the git repo folder, we can extract that. This works when you didn't make any additional commits immediately after deletion a.k.a realizing your mistake sooner.
``` 
git checkout -- index.html
```
# Scenario -2
>### 1. You did this.
>> git rm index.html
>>> This removes index.html from Both your working directory and staging area

# Solution for Scenario-2

### This is a 2 step process
``` 
git reset HEAD index.html
```
This unstages the deletion

Follow it up by:
```
git checkout -- index.html
```
# Scenario-3
>### 1. You made a commit of a file, say *index.html*
>### 2. After the commit was made, the file has been removed
>### 3. Now the file is no longer with you in your working directory.
>### 4. You went ahead and made a commit of the deletion.
>### 5. You later realised that you need that file from that specific commit

# Solution for Scenario-3

### Yup, a version of this file exists as commit in the git repo folder, This can be done.

```
git reset --hard HEAD^
```
### This resets the commit by one. That is the (^ - caret symbo) Its a hard reset meaning the hash from the git log is also gone.

Now the HEAD will point to the previous commit, before the deletion.

### File can be retrieved by simply using,
```
git checkout -- index.html
```