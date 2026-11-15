# Mission 6 — Git and GitHub

## 1. Task / objective
Use the basic Git workflow, create a branch, and open a Pull Request.

## 2. Work completed

Checked status, staged, committed and viewed history. Created branch `update-about`, added "My Learning" to the root README, pushed the branch and opened a PR into `main`. PR status: [merged / open, not merged].

### Task 6.1 — Understand the basic Git workflow



## 3. Commands / tools used

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
[Your words. Cues:]
- Staging picks what goes into the next commit; committing records it permanently.
- A branch is a separate line of work that doesn't affect `main` until merged.
- A Pull Request asks to merge a branch into another, so others can review the change first.
- Useful for teamwork: people work in parallel without overwriting each other.

## 5. Difficulties faced
[Your honest answer]

## 6. How I resolved them
[Or "Not applicable"]

## 7. Evidence / files
This README; PR and branch visible on GitHub; screenshot in `evidence/` (optional).

## 8. Commit details
"Complete Git and GitHub collaboration mission" — pushed and verified. PR status: [state it].