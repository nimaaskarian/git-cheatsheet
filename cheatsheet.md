# Git cheatsheet!
Use this to learn git, don't be lazy.
## Setup
Set the name and email that'll be attached to your commits and tags.
- `git config --global user.name "Nima Askarian"`
- `git config --global user.email "my-email@mail.com"`
## Start a project

- Either initialize a directory with git (create a local repo) and add a remote (optional)
  1. `git init <directory>`  
  **Optional (if you want to initialize remote with your local repo):**
  2. `git remote add <name> <url>`
  3. `git push --set-upstream <remote> <branch>`
- Or download a remote repo  
  `git clone <url>`

## Make a change
- Stage a file  
`git add <file>`
- Stage all files  
`git add <file>`
- Commit staged changes  
`git commit -m "commit message"`
- Commit changes to tracked files  
`git commit -am "commit message"`

## Basic concepts
**main**: default development branch  
**origin**: default upstream repo (remote)
**HEAD**: current branch
**HEAD^**: parent of HEAD
**HEAD~3**: great grandparent of HEAD
