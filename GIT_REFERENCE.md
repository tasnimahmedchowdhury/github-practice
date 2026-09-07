# Git Reference

A concise reference of Git and GitHub concepts and commands practiced in this repository.

## Core Concepts

### Git

Git is a distributed version control system used to track changes to files and maintain project history.

### GitHub

GitHub is a platform for hosting Git repositories and collaborating on software projects.

### Working Directory

The files currently being viewed and edited.

### Staging Area

Changes selected to be included in the next commit.

### Commit

A saved checkpoint in the repository history.

### Remote

A version of the repository hosted elsewhere, such as on GitHub.

### Branch

An independent line of development that allows work to be isolated from the main branch.

## Basic Workflow

1. Modify files
2. Inspect repository state with `git status`
3. Review unstaged changes with `git diff`
4. Stage selected changes with `git add`
5. Review staged changes with `git diff --staged`
6. Create a checkpoint with `git commit`
7. Synchronize commits with GitHub using `git push`

## Commands Practiced

| Command | Purpose |
| --- | --- |
| `git status` | Show the current repository state |
| `git diff` | Show unstaged changes |
| `git diff --staged` | Show staged changes |
| `git add <file>` | Stage changes for the next commit |
| `git commit -m "message"` | Create a commit |
| `git log` | Inspect commit history |
| `git push` | Send local commits to a remote repository |
| `git pull` | Retrieve and integrate remote changes |
| `git branch` | List or manage branches |
| `git switch <branch>` | Switch to another branch |
| `git switch -c <branch>` | Create and switch to a new branch |
| `git merge <branch>` | Merge another branch into the current branch |
| `git restore <file>` | Discard unstaged changes to a tracked file |
| `git rm <file>` | Remove a tracked file and stage the deletion |
| `git mv <old> <new>` | Rename or move a tracked file |

This reference will be expanded as additional Git and GitHub workflows are practiced.
