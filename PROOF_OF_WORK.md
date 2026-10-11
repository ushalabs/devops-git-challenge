# PROOF OF WORK

## DevOps Class Activity

Student Name: M. Usman
SAP ID: [Your SAP ID]

## 1. Git Commit History

Command Used: git log --oneline

16ffe97 (HEAD -> main, origin/main) Merge pull request #1 from ushalabs/development
7ed5ec6 (origin/development, development) fix: resolved merge conflict
ff54cbe (origin/staging, staging) fix: staging label
ec03ad1 feat: updated script with staging env
5b7c822 feat: initial commit with deploy script

## 2. Reflection Questions

### Q1: Difference between Git and GitHub

Git is a version control tool that helps developers track
changes in their code locally. It allows us to create commits,
manage branches, and restore previous versions of files.
GitHub is an online platform where we can store Git
repositories and collaborate with other developers.
Git works locally, while GitHub provides remote storage
and collaboration features like Pull Requests.

### Q2: Explain Working Directory, Staging Area, and Local Repository

The Working Directory is where we create and modify
our project files. The Staging Area is where we place
selected changes using the git add command before
committing them. The Local Repository stores our
committed changes and their history on our computer.
These three stages help us organize and control how
changes are saved in Git.

### Q3: Difference between git stash pop and git stash apply

Both commands are used to restore changes that were
temporarily saved using git stash. The git stash pop
command applies the saved changes and removes the stash
entry if the application is successful. On the other hand,
git stash apply restores the changes but keeps the stash
entry for future use. This makes stash apply useful when
we want to reuse the same saved changes.

### Q4: Difference between git fetch and git pull

The git fetch command downloads new commits and branch
information from a remote repository without automatically
merging them into our current branch. The git pull command
downloads remote changes and then integrates them into
our current branch, normally by merging or rebasing.
We can use git fetch when we want to review changes first.
Git pull is useful when we want to update our local branch
directly.