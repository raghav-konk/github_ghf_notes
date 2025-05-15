# Github Notes for GHF Test
This repo contains notes for Github Foundations Test


# Environement Setup

Goal is to install Git and then setup user details and then follow it up by configuring it with GitHub with a PAT -Token.


# 1. Installation on Linux (Debian Based)
```
sudo apt-get update
```
Follow it up by:
```
sudo apt-get install git-all
```

# 2. Checking the Current Version (If incase you already have it installed)

```
    git --version
```

# 3. Configuring the Username and Email 
Git requires a username and email in order to track who committed what in a team. These are kept in track by Username and Email. 
Lets set that up.
This process is independent of Github

```
git config --global user.name "Raghav"
git config --global user.email raghavendra.konkathi@gmail.com
```