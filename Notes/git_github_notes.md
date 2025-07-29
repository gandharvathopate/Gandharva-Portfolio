# 🚀 GitHub Command Reference (Code-Only)

## 🔧 Git Setup
```bash
git config --global user.name "Your Name"
git config --global user.email "your@example.com"
git config --global color.ui auto
```

## 📁 Create / Clone Repository
```bash
git init
git clone https://github.com/your-username/your-repo.git
```

## ✅ Stage & Commit
```bash
git status
git add .
git commit -m "Initial commit"
```

## 📤 Push to GitHub
```bash
git remote add origin https://github.com/your-username/your-repo.git
git push -u origin main
```

## 🌱 Branching
```bash
git branch
git branch new-feature
git checkout new-feature
git merge main
```

## 🔄 Pull & Update
```bash
git pull origin main
git fetch origin
```

## 🔥 Stashing Changes
```bash
git stash
git stash list
git stash pop
```

## 🧹 Undo / Reset
```bash
git reset <file>
git reset --hard <commit>
git restore <file>
```

## 📦 Ignore Files
```bash
# .gitignore example
node_modules/
*.log
