# 🧠 Philosophers Project - Git Commands Cheat Sheet

This file contains a complete list of essential Git commands with explanations, useful for both 42 School projects and real-world development.

---

## 🔧 Setup and Config

| Command | Description |
|--------|-------------|
| `git config --global user.name "Your Name"` | Set your Git username |
| `git config --global user.email "you@example.com"` | Set your Git email |
| `git init` | Initialize a new Git repository |
| `git clone <url>` | Clone a remote repository |

---

## 📝 Working with Changes

| Command | Description |
|--------|-------------|
| `git status` | Show the current working status |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage all changed files |
| `git commit -m "message"` | Commit changes with a message |
| `git diff` | View unstaged changes |
| `git diff --staged` | View staged changes |

---

## 🔁 Branching

| Command | Description |
|--------|-------------|
| `git branch` | List local branches |
| `git branch <name>` | Create a new branch |
| `git checkout <branch>` | Switch to another branch |
| `git checkout -b <name>` | Create and switch to a new branch |
| `git merge <branch>` | Merge another branch into current |

---

## 🌐 Remote Repositories

| Command | Description |
|--------|-------------|
| `git remote -v` | View linked remotes (GitHub, etc.) |
| `git fetch` | Fetch new commits from remote without merging |
| `git pull` | Fetch and merge changes from remote |
| `git push` | Push local commits to remote |
| `git push --force` | Force push (caution: overwrites history) |

---

## 🧹 Cleanup and Reset

| Command | Description |
|--------|-------------|
| `git rm <file>` | Delete a file from repo and disk |
| `git rm --cached <file>` | Stop tracking a file (keep it locally) |
| `git clean -fd` | Remove all untracked files and directories |
| `git reset HEAD <file>` | Unstage a file (keep changes) |
| `git restore <file>` | Restore file from last commit |

---

## 📜 History & Logs

| Command | Description |
|--------|-------------|
| `git log` | View commit history |
| `git log --oneline --graph --all` | Visualize branches and commits |
| `git show <commit>` | Show changes in a commit |

---

## 🔍 Comparing Changes

| Command | Description |
|--------|-------------|
| `git diff` | Compare working dir with index |
| `git diff HEAD` | Compare working dir with last commit |
| `git diff main origin/main` | Compare local vs remote branch |
| `git diff <branch1> <branch2>` | Compare two branches |

---

## 📦 Ignoring Files

| Command | Description |
|--------|-------------|
| `echo ".idea/" >> .gitignore` | Add JetBrains IDE folder to ignore list |
| `git rm -r --cached .idea/` | Remove .idea from tracking (keep locally) |
| `git commit -m "Ignore .idea"` | Commit the ignore rule |

---

## 🛠 Advanced History and Conflict Tools

| Command | Description |
|--------|-------------|
| `git rebase <branch>` | Move your commits on top of another branch |
| `git cherry-pick <commit>` | Apply a commit to current branch |
| `git revert <commit>` | Create a new commit that undoes an old one |
| `git stash` | Temporarily hide uncommitted changes |
| `git stash pop` | Restore stashed changes |

---

## 🧪 Safe Git Workflow (Daily Use)

```bash
git status            # What changed?
git add .             # Stage all changes
git commit -m "..."   # Save changes
git pull --rebase     # Sync with remote
git push              # Upload work

