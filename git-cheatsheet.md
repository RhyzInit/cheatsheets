# Git Cheatsheet — Beginner's Guide

## Setup

| Task                    | Command                      |
|-------------------------|------------------------------|
| Set user name           | `git config --global user.name "Your Name"` |
| Set user email          | `git config --global user.email "you@example.com"` |
| Initialize new repo     | `git init`                   |
| Clone existing repo     | `git clone <repo-url>`       |

---

## Basic Workflow

| Task                    | Command                      |
|-------------------------|------------------------------|
| Check repo status       | `git status`                 |
| Add files to staging    | `git add <file>` or `git add .` (all files) |
| Commit changes          | `git commit -m "Commit message"` |
| View commit history     | `git log`                   |
| Show changes (diff)     | `git diff`                  |

---

## Branching & Merging

| Task                    | Command                      |
|-------------------------|------------------------------|
| List branches           | `git branch`                 |
| Create a new branch     | `git branch <branch-name>`   |
| Switch branches         | `git checkout <branch-name>` or `git switch <branch-name>` |
| Create and switch branch| `git checkout -b <branch-name>` or `git switch -c <branch-name>` |
| Merge branch into current| `git merge <branch-name>`   |
| Delete a branch         | `git branch -d <branch-name>` (safe delete) |

---

## Remote Repositories

| Task                    | Command                      |
|-------------------------|------------------------------|
| Show remotes            | `git remote -v`              |
| Add a remote            | `git remote add origin <url>` |
| Push branch to remote   | `git push origin <branch-name>` |
| Push and set upstream   | `git push --set-upstream origin <branch-name>` |
| Pull changes from remote| `git pull`                   |
| Fetch changes from remote| `git fetch`                 |

---

## Undoing Changes

| Task                    | Command                      |
|-------------------------|------------------------------|
| Unstage a file          | `git reset HEAD <file>`      |
| Discard changes in file | `git checkout -- <file>`     |
| Undo last commit (keep changes staged) | `git reset --soft HEAD~1` |
| Undo last commit (discard changes) | `git reset --hard HEAD~1` |

---

## Tips

- Use `git switch` instead of `git checkout` for switching branches (modern and clearer).
- Use `git restore` to discard changes (instead of `checkout --`).
- Use descriptive commit messages for clarity.

---

Happy coding with Git! 🚀