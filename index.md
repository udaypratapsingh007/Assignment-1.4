# Assignment 1.4 - Git Essentials I

## Task

Convert a local project into a Git repository and make three commits.

## Terminal Commands

```bash
git --version
cd web-development-practice
git init
git config --global user.name "Your Name"
git config --global user.email "your@email.com"
type nul > index.html
git status
git add index.html
git commit -m "Add index.html file"
echo ^<h1^>Hello World^</h1^> > index.html
git add index.html
git commit -m "Add heading to index.html"
type nul > style.css
git add style.css
git commit -m "Add style.css file"
git log --oneline
```

## Explanation

- `git --version` checks that Git is installed.
- `git init` turns the project folder into a Git repository.
- `git config` sets the username and email that are attached to every commit.
- `git status` shows which files are new, changed or staged.
- `git add` moves changes to the staging area.
- `git commit -m` saves the staged changes as a commit with a message.
- `git log --oneline` shows the commit history in a short form.

## Commits Made

1. Add index.html file
2. Add heading to index.html
3. Add style.css file