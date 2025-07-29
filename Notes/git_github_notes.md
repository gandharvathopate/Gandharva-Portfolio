# 🧠 GitHub & Git Basics
This guide covers the most commonly used Git commands and GitHub practices to help beginners manage projects, collaborate, and contribute efficiently.



## 🛠️ Setup Git

Before starting, configure your identity:

git config --global user.name "Your Name"
git config --global user.email "you@example.com"
git config --global color.ui auto



## 📂 Create or Clone a Repository

git init # Initialize a Git repository in your folder
git clone <url> # Copy an existing repository from GitHub



## ✅ Stage & Commit Changes

git status # View modified files
git add <file> # Stage a specific file
git add . # Stage all files
git diff # See unstaged changes
git diff --staged # See staged changes
git commit -m "message" # Commit staged changes



## 🔁 Undo / Reset

git reset <file> # Unstage a file, keep changes
git reset --hard <commit> # Revert to a specific commit (DANGER!)



## 🌱 Branching & Merging

git branch # List branches
git branch <name> # Create a new branch
git checkout <name> # Switch to a branch
git merge <branch> # Merge another branch into current
git log # Show commit history



## 🌐 Collaborate with GitHub

git remote add origin <url> # Link local repo with GitHub
git fetch # Fetch remote changes
git pull # Pull changes and merge
git push # Push local commits to GitHub



## 🔁 Move / Delete Files

git rm <file> # Delete and stage for commit
git mv old new # Rename a file



## 🔍 Inspect Changes

git log --stat # Commit log + file changes
git log --follow <file> # Log for a specific file, including renames
git diff branchA..branchB # Compare branches
git show <SHA> # Show commit or file details by hash



## 🔒 Stashing Temporary Changes

git stash # Save changes temporarily
git stash list # View stashed changes
git stash pop # Reapply stashed changes
git stash drop # Delete latest stash



## 🧹 Ignore Unwanted Files

Create a `.gitignore` file in your project root:

logs/
*.log
*.tmp
node_modules/



## 👥 GitHub GUI Tools

- GitHub Desktop (Windows/Mac): https://desktop.github.com/
- GitHub Web Interface: https://github.com/
- Git for All Platforms: https://git-scm.com/



## 🎓 Recommended for Students

- GitHub Education Pack: https://education.github.com/
- Interactive Git Learning: https://learngitbranching.js.org/
- GitHub Docs: https://docs.github.com/en



> 🧠 **Pro Tip**: Make frequent commits with meaningful messages. Version control is not just for code—use it for notes, reports, projects, and more!