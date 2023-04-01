# Git-and-GitHub-for-Beginners-Tutorial

## GitHub

is a hosting platform where you can collaborate with others in git repository

## What is Git

is open source and free source control management (SCM)

### If git installed

```bash
git --version
```

### to get help about command

```bash
git theCommandYouNeed -h
```

Or

```bash
git help theCommandYouNeed
```

### to config git

```bash
git config --global user.name "YourUserName"
git config --global user.email YourUserEmail
```

### to set the default branch

```bash
git config --global init.default branch main
```

### Create empty git repository

```bash
git init
```

### Check the status of git repository

```bash
git status
```

### to see what has been modified

```bash
git diff
```

### to restore the changes

```bash
git restore <file/directory name 1> <file/directory name 2> < ... >
```

### to ignore files

add the file or folder name or bath or add \*.file extinction to ignore all files that have that extinction
to .gitignore file

### add files to the repository

```bash
git add <file/directory name 1> <file/directory name 2> < ... >
```

Or add all

```bash
git add .
```

```bash
git add -A
```

Or

```bash
git add --all
```

### to unstage file

```bash
git rm --cashed <file/directory name 1> <file/directory name 2> < ... >
```

Or

```bash
git restore --staged <file/directory name 1> <file/directory name 2> < ... >
```

### Commit all the files that have been added along with message

```bash
git commit -m "the message"
```

OR to skip staging and commit all file

```bash
git commit -a -m "the message"
```

### to change the commit message

```bash
git commit -m "the new message" -- amend
```

### to review the commits

```bash
git log
```

Or in one line

```bash
git log --oneline
```

or to see in detail's

```bash
git log -p
```

### to reset the commit

```bash
git reset theGitHashTag
```

### create new branch

```bash
git branch NewBranchName
```

### to show all branch's

```bash
git branch
```

### to switch to branch

```bash
git switch BranchName
```

### add new remote

```bash
git remote add origin https://<your-git-service-address>/owner/repository.git
```

### Clone repository

```bash
git clone https://github.com/username/projectname.git
```

or to Clone repository in folder

```bash
git clone https://github.com/username/projectname.git MyFolder
```

or to clone repository in current directory

```bash
git clone https://github.com/username/projectname.git .
```
