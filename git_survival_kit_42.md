# 🧠 Git Survival Kit – Commands Cheat Sheet

A complete, beginner-to-pro-ready Git command reference for:

- 🏫 42 School students  
- 🧑‍💻 Developers of all levels  
- ✅ Clean workflows and safe collaboration  

---

## 🔧 Git Setup

| Command | Description |
|--------|-------------|
| `git config --global user.name "Your Name"` | Set your Git username |
| `git config --global user.email "you@example.com"` | Set your Git email |
| `git init` | Start a new Git repo in your current folder |
| `git clone <url>` | Download a copy of a remote GitHub repo |

---

## 📝 Stage and Commit Changes

| Command | Description |
|--------|-------------|
| `git status` | See what’s modified, staged, or untracked |
| `git add <file>` | Stage a specific file |
| `git add .` | Stage everything (including new files) |
| `git commit -m "message"` | Save a snapshot of staged files |

---

## ✏️ Undo and Restore

| Command | Description |
|--------|-------------|
| `git restore <file>` | Undo changes in working directory |
| `git restore --staged <file>` | Unstage a file (keep changes) |
| `git reset HEAD <file>` | Also unstages a file (older syntax) |
| `git checkout -- <file>` | Old command to discard changes |

---

## 🔁 Branching and Merging

| Command | Description |
|--------|-------------|
| `git branch` | List branches |
| `git branch <name>` | Create a new branch |
| `git checkout <name>` | Switch branches |
| `git checkout -b <name>` | Create + switch to a new branch |
| `git merge <name>` | Merge branch `<name>` into current |

---

## 🌐 Working with Remotes

| Command | Description |
|--------|-------------|
| `git remote -v` | Show connected remotes (e.g. GitHub) |
| `git fetch` | Get updates from remote (no merge) |
| `git pull` | Fetch + merge remote changes |
| `git pull --rebase` | Fetch + rebase (cleaner history) |
| `git push` | Upload your commits to GitHub |
| `git push --force` | Push with overwrite (be careful) |

---

## 🧹 Clean Up & Untrack Files

| Command | Description |
|--------|-------------|
| `git rm <file>` | Delete file from disk and staging |
| `git rm --cached <file>` | Stop tracking but keep file locally |
| `git clean -fd` | Delete untracked files and folders |
| `echo ".idea/" >> .gitignore` | Ignore JetBrains IDE folder |
| `git rm -r --cached .idea/` | Remove `.idea/` from Git tracking |

---

## 📜 History and Logs

| Command | Description |
|--------|-------------|
| `git log` | Full commit history |
| `git log --oneline` | Short history format |
| `git log --graph --oneline --all` | Visual tree of branches |
| `git show <commit>` | See what a commit changed |

---

## 🔍 Compare Changes

| Command | Description |
|--------|-------------|
| `git diff` | Show changes not yet staged |
| `git diff --staged` | Show staged changes |
| `git diff main origin/main` | Compare local branch vs GitHub |
| `git diff <branch1> <branch2>` | Compare two branches |

---

## 🛠️ Advanced Tools

| Command | Description |
|--------|-------------|
| `git rebase <branch>` | Replay commits on top of another branch (linear history) |
| `git cherry-pick <commit>` | Apply a specific commit |
| `git revert <commit>` | Create a commit that undoes another |
| `git stash` | Save dirty changes and clear working dir |
| `git stash pop` | Reapply latest stash |

---

## 🧪 Safe Git Workflow (Daily Use)

```bash
git status             # See what changed
git add .              # Stage all changes
git commit -m "Update" # Save a snapshot

# Use this for clean history:
git pull --rebase      

# Or this if you're new or prefer merge commits:
# git pull

git push               # Upload to GitHub

