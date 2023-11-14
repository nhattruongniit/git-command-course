```bash
# use global config
$ git config --global user.name "truong.nn"
$ git config --global user.email "truong.nn@gmail.com"

# use local config for each project
$ git config --local user.name "tony"
$ git config --local user.email "tony@gmail.com"

# view your setting
$ git config --list

# view origin your setting
$ git config --list --show-origin
```

```bash
# Initializing a Repository in an Existing Directory
$ git init

# Add files to staging area
$ git add .

# Commit changes in staging area
$ git commit -m "first commit"

# Switch to a branch
$ git branch -M main

# Add a remote repository
$ git remote add origin https://github.com/nhattruongniit/git command-course.git

# Push changes to a remote repository
$ git push -u origin main
```

```bash
# Clone a repository

# Clone with HTTPS
$ git clone https://github.com/nhattruongniit/git-command-course.git

# Add files to staging area
$ git add .

# Commit changes in staging area
$ git commit -m "message commit"

# Push changes to a remote repository
$ git push
```

```bash
# get latest changes from remote repository
$ git pull

# merge branch
$ git merge <name branch>

# stash changes
$ git stash

# pop changes
$ git pop
```

```bash
$ git revert <commit SHA>
```

```bash
$ git reset --soft
```
