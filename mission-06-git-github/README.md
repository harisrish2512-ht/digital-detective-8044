# Mission 6 — Git and GitHub

## 1. Task / objective
Use the basic Git workflow, create a branch, and open a Pull Request.

## 2. Work completed

Checked status, staged, committed and viewed history. Created branch `update-about`, added "My Learning" to the root README, pushed the branch and opened a PR into `main`. PR status: [merged / open, not merged].

### Task 6.1 — Understand the basic Git workflow

| Git Operation | What it does in my own words |
|---|---|
| Check repository status | shows current branch and the changes made in that branch |
| Stage selected changes | Only a particular file or folder is staged for upcoming commit |
| Create a commit | saves a snapshot of everything I staged with commit message |
| View commit history | shows all the commits done in the repository with commit message and time |

### Task 6.2 — Create and use a branch

Create a new branch `update-about` and modified root README.md by adding "My Learnings" section.

### Task 6.3 — Create a Pull Request

Created a pull request to merge the new branch `update-about` to the `main` branch. Reviewed the changes and merged the two branches via the PR.

#### Pull Reuqest

A Pull Request (PR) is a request on GitHub to merge the changes from one branch into another, usually from your feature branch into main. It shows exactly which files and lines changed, and it gives other people a place to review, comment on and approve the changes before they become part of the main project. The name comes from you asking the project to “pull” your changes in.

In this assignment, I pushed update-about, open a PR from update-about into main, described the README change, and reviewed the changed file.

## 3. Commands / tools used

### Task 6.4 — Build your Git command glossary

| Operation | Command | What it does |
|---|---|---|
| Initialise | `git init` | Starts a repository in a folder |
| Check status | `git status` | Shows changed and staged files |
| Stage | `git add README.md` | Selects changes for the next commit |
| Commit | `git commit -m "msg"` | Saves the staged snapshot to history |
| View history | `git log --oneline` | Lists past commits |
| Branches | `git branch` / `git switch -c update-about` | Lists / creates a branch |
| Switch | `git switch main` | Moves to another branch |
| Publish | `git push -u origin update-about` | Uploads commits to GitHub |
| Retrieve | `git pull` | Downloads and merges remote changes |

## 4. My understanding

- git add: Staging picks what goes into the next commit , git commit: committing records it permanently.
- A branch is a separate line of work that doesn't affect the `main` branch until merged.
- A Pull Request asks to merge a branch into another, so others can review the change first.
- Useful for teamwork: people work in parallel without overwriting each other.

## 5. Difficulties faced

I felt little difficulty in raising a PR and merging it.

## 6. How I resolved them

I asked my friends and also learnt from google and AI.

## 7. Evidence / files

This README; PR and branch visible on GitHub; screenshot in `evidence/Mission 6.png` , `evidence/Mission 6.3.png`

## 8. Commit details
"Complete Git and GitHub collaboration mission" — pushed and verified. PR status: [state it].