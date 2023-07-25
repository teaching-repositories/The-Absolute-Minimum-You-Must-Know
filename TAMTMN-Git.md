# Git: The Absolute Minimum You Must Know 

Git is a version control system that lets you manage changes to your code over time. Here's what you need to know to get started with Git:

## Initialize a Repository

To start tracking a project, navigate to the directory and initialize a new Git repo:

```
git init
```

This will create a `.git` folder to store your commits. 

## Check Status

See changed files in your repo with:

```
git status
```

## Stage Files 

Stage files to prepare them for commit using:

```
git add <filename> 
```

## Commit Changes

Commit staged changes with a message:

```
git commit -m "Message describing changes"
```

## Push to Remote

Send commits to a remote repo like GitHub: 

```
git push origin main
```

That covers the basic Git workflows! You can now track changes, commit them locally, and push to a remote repository.