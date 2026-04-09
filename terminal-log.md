# Terminal Command Log

## 📌 Navigation

```bash
pwd
ls
cd projects
mkdir js-assignment
cd js-assignment
```

## 📌 File Creation

```bash
touch index.html script.js README.md .gitignore
```

## 📌 Git Initialization

```bash
git init
git status
```

## 📌 First Commit

```bash
git add .
git commit -m "Initial project setup"
```

## 📌 Adding More Changes

```bash
git add script.js
git commit -m "Add calculator functionality"

git add grades.js
git commit -m "Add student grade tracker"
```

## 📌 Branching

```bash
git branch feature-ui
git checkout feature-ui
```

## 📌 Working on Branch

```bash
git add .
git commit -m "Update UI for calculator"
```

## 📌 Merging

```bash
git checkout main
git merge feature-ui
```

## 📌 Connecting to GitHub

```bash
git remote add origin https://github.com/your-username/js-project.git
git push -u origin main
```
