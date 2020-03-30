# Practice repository to start learning git

## Commands used

- git init: Create a repository
- git status: Compare working directory, staging area, and current branch
- git add: Add Changes from working directory to staging area
- git commit: Commit changes from staging area to current branch
- git config: Set or get configuration
- git log: Show history of project commits
- git branch: list branches
- git checkout -b: Create branch, then check it out

## What's a branch?

A branch is a ref(erence) to a commit.  When head points to a branch we saw we are on that branch.  When we make a commit when we are on that branch, the branch is updated to ref(er) to the new commit.

## What's HEAD?

HEAD is a ref(erence) to the "current" branch (or sometimes a commit).  Git commands like 'status', 'log', and 'branch' use HEAD. 'git checkout' updates HEAD to ref(er) to a different branch.

## Commit messages

Default editor is vim (this can be changed)
  - 'i' to enter *insert* mode
  - Type commit message
  - 'ESC' -> ':wq' -> 'Enter' to write message and quit
or use 'git commit -m "<message>"

- First line should be clear, accurate and concise
- Use proper spelling, grammar, and punctuation
- Don't end with a '.'

For more advice, see: https://chris.beams.io/posts/git-commit/
