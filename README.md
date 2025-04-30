---
# 🧠 Git Survival Kit

![Git](https://img.shields.io/badge/Git-Command%20Line-red?style=flat-square)
![Markdown](https://img.shields.io/badge/Format-Markdown-blue?style=flat-square)
![42 School](https://img.shields.io/badge/42Network-Compatible-brightgreen?style=flat-square)
![Beginner Friendly](https://img.shields.io/badge/Level-All-blueviolet?style=flat-square)

A clean, beginner-friendly, and professional Git command reference for:

- 🏫 42 School projects
- 🧑‍💻 Day-to-day developer workflows
- 🧠 Learning or teaching Git

---

## 📘 What's Inside?

This Markdown file includes:

- ✅ Basic Git setup and configuration
- ✅ Staging, committing, and undoing changes
- ✅ Branching, merging, pushing, and pulling
- ✅ Comparing branches and commits
- ✅ Handling `.gitignore`, untracked files, and cleanups
- ✅ Advanced tools like rebase, stash, and cherry-pick
- ✅ A daily Git workflow reference

---

## 📁 Repository Structure

```bash
.
├── git_cheat_sheet.md       # Full Git guide
├── README.md                # This file
```

---

## 🚀 How to Use

```bash
git clone https://github.com/kitearuba/git-survival-kit.git
cd git-survival-kit
cat git_cheat_sheet.md
```

Or open `git_cheat_sheet.md` in your favorite Markdown viewer:
- VSCode
- Obsidian
- Typora
- GitHub

---

## 🧠 Sample Highlights

### 🔁 Branching
```bash
git checkout -b feature/login-page
git merge main
```

### 🧹 Ignore & Untrack Files
```bash
echo ".idea/" >> .gitignore
git rm -r --cached .idea/
git commit -m "Ignore IDE files"
```

### 💣 Daily Safe Workflow
```bash
git add .
git commit -m "Update"
git pull --rebase
git push
```

---

## 🤝 Contribute

Have a trick or tip to share?  
PRs and improvements are welcome to help others learn Git more easily.

---

## 👨‍💻 Author

- **Christian Rodriguez (chrrodri)**  
- 🏫 42 Barcelona  
- 🌍 GitHub: [@kitearuba](https://github.com/kitearuba)  
- 📅 Created: April 2025  
- 📚 Repo: [`git-survival-kit`](https://github.com/kitearuba/git-survival-kit)

---

## 📜 License

MIT License — use freely, contribute if you’d like, and share with others.
---
