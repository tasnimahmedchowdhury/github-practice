# Git & GitHub Learning Log

This log documents hands-on Git and GitHub practice, including the concepts, commands, and workflows I have applied.

## 2026-09-07 — Git/GitHub Day 1

### Topics Practiced

- Reviewed the working directory, staging area, local repository, and remote repository workflow
- Inspected repository state with `git status`
- Reviewed unstaged changes with `git diff`
- Reviewed staged changes with `git diff --staged` and `git diff --cached`
- Used `git restore` to safely discard unintended changes
- Staged changes with `git add`
- Created descriptive commits with `git commit`
- Synchronized local commits with GitHub using `git push`
- Inspected commit history with `git log`
- Created and switched branches with `git switch -c`
- Used `git branch` to inspect and manage branches
- Made and committed changes independently on a feature branch
- Switched between branches and observed branch-specific file states
- Merged a feature branch into `main`
- Observed a fast-forward merge
- Deleted a merged temporary branch
- Removed tracked files with `git rm`
- Renamed and reorganized tracked documentation with `git mv`
- Reviewed repository changes before publishing them
- Reorganized the repository into clean public-facing documentation

### Key Takeaways

- The working directory contains files currently being edited.
- The staging area contains changes selected for the next commit.
- `git diff` helps identify unintended edits before they are committed.
- `git diff --staged` shows exactly what is prepared for the next commit.
- Commits create meaningful checkpoints in repository history.
- Branches allow changes to be developed independently from `main`.
- A fast-forward merge can occur when `main` has not diverged from the feature branch.
- A merged branch can be deleted without deleting commits already merged into `main`.
- Git tracks file additions, modifications, deletions, and renames through repository history.
- Reviewing status and diffs before committing helps keep public repositories clean.

### Practice Repository

`github-practice`

**Session completed:** 2026-09-08 00:00:53 +06:00
