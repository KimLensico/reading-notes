# GIT TUTORIAL NOTES

## What is Git?
> Git is a DVCS that stores date in a file system made up of snapshot. Each time you save a changed version (commit) Git creates a snapshot of the file and stores a reference to it.

- relies on local operations - every single change is tracked by git
- set up to greatly minimize the possibility of irreversible damage to files such as lost date

States - Git files reside in three main states: 
1. Commit 
2. Modified 
3. Staged

## What is GitHub?

 - hub- focused tool which facilitates Integration-Manager Workflow.
- largest existing host for Git repositories and is used by millions of developers worldwide.

## Workflow
- Local Repository Structure: the local Git repository has three components:

1. Working Directory: The actual files reside here.
2. Index: The area used for staging
3. Head: Points to the most recent commit


## MOST IMPORTANT COMMANDS TO REMEMBER: (A) (C) (P)
codes to track repository:


```
track files in depository: git add . 
commit snapshot of modification: git commit -m "Made changes to text files"
to push changes: git push origin master 
``` 
 other codes:

```
clone github repo: git clone https://github.com/test 
shows all remote urls in their short names: git remote -v 
```

for more in depth information: [click here](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/) 


[<==back](README.md)
