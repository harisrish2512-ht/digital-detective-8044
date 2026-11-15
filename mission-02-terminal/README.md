# Mission 2 — Become comfortable with the Terminal

## 1. Task / objective
Use basic commands to navigate and manage files, understand flags and pipes, and explain package managers.

## 2. Work completed
Practised file commands, created `terminal-practice/` with `notes.txt` (two lines), a backup and a renamed copy, compared `ls` flags, used a pipe, and checked Homebrew .

### Task 2.1  — Explore basic Terminal operations

| Operation | Command | What it does | What I observed |
|---|---|---|---|
| Current directory | `pwd` | Prints the full path of where I am | /Users/harisriht/Desktop/digital-detective-8044 |
| Directory listing | `ls` | Lists files and folders | Names of folders present only |
| Detailed listing | `ls -l` | Lists with permissions, size, date | Extra columns appeared |
| Change directory | `cd ..` | Moves to the parent folder | `pwd` showed a shorter path |
| Create directory | `mkdir practice` | Makes a folder | Folder appeared in `ls` |
| Create empty file | `touch a.txt` | Makes an empty file | File of size 0 |
| Copy file | `cp a.txt b.txt` | Duplicates a file | Both files exist |
| Move/rename | `mv b.txt c.txt` | Renames or relocates | `b.txt` gone, `c.txt` exists |
| Display contents | `cat a.txt` | Prints file contents | Nothing (empty file) |

### Task 2.2 — Practise file changes safely

Replacing contents vs adding to the end:
- `>` replaces a file's contents; `>>` adds to the end.
Copying vs moving a file:
- Copy keeps the original; move relocates or renames it.
What information does the current-directory display provide?
- `pwd` shows exactly where commands will act.
Why is a directory-listing operation useful?
- `ls` shows what exists in a folder.

### Task 2.3 — Understand flags and pipes

Normal listing vs detailed listing: ls only shows the names of the files and folders. ls -l shows one item per line with the permissions, owner, size and date.

Comparing ls -l and ls -lah: What changed from ls to ls -lah is that I can see hidden files such as .git
A flag changes the command’s behaviour. ls alone is a short list. Adding flags gave me more detail, hidden files and readable sizes, without using a different command.

The pipe | sends the output of the left command into the right command as its input. Here ls -l produces the listing and head -5 trims it to five lines.

### Task 2.4 — Understand package managers

Commands used:

- brew --version: shows which version of Homebrew is installed
for me it showed -> Output: Homebrew 7.0.9
- brew list: lists the packages Homebrew is managing
for me it showed -> Output: refer evidence

## 3. Commands / tools used

pwd, ls, ls -l, ls -lah, cd, mkdir, touch, cp, mv, cat, brew --version, brew list.

## 4. My understanding

I used and revised appropriate commands needed to perform the tasks. It was a revision tour on the basic CLI commands.

## 5. Difficulties faced

I faced no difficulties as am clear with basic CLI commands.

## 6. How I resolved them

Not Applicable

## 7. Evidence / files
![alt text](<Screenshot 2026-11-15 at 9.47.17 PM.png>)
![alt text](<Screenshot 2026-11-15 at 10.14.03 PM.png>)

## 8. Commit details
"Complete Terminal and file management mission" — pushed and verified.