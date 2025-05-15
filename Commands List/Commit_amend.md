# So we are left with a unique predicament here

### We created a file added some lines of code to it. Then proceeded to commit.



### But, the file in question required very minor changes such as typo or a syntax error.

#### We corrected that error but now we want to commit it,But instead of creating a new commit, We merely want to edit the past commit where this change should belong to.

How do we that?

## Amending the commit
```
git commit --amend --no-edit
```
This keeps the same commit message but amends the content to the correction that was made later to the file.

## Why?
1. This keeps the commit history clean and organised
2. Avoids overcrowding of the commit chain.

**Note:** Internally, git in fact creates a new commit hash for this amendment, However the commit message remains the same.