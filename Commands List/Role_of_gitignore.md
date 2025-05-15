# Role of .gitignore file.

Say if your repo folder contains a file called notes.txt which is irrelevant to the project but is there as a guide specific to you and serves no other purpose. Alternatively, we can also add any temporary files that we don't want git to track in the repository to keep the contents clean and organised.

### So how do we tell Git not to track this notes.txt file.
1. We create a file called .gitignore (no file extension needed)
2. We add this notes.txt to this .gitignore file by simply editing the .gitignore file. Just add its name
3. We can rinse and repeat for any files that we'd like to be ignored. Adding the filename to .gitignore file
