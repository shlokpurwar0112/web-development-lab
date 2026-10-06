# Experiment 1 – GitHub Repository, Branches, Merge and GitHub Pages

## Objective
Set up a GitHub repository, create a branch, make changes, merge the branch into `main`, and host the project using GitHub Pages.

## Commands
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin YOUR_REPOSITORY_URL
git push -u origin main

git checkout -b feature
git checkout feature
# Make a change to any file
git add .
git commit -m "Update from feature branch"
git push -u origin feature
```

On GitHub:
1. Open the repository.
2. Create a Pull Request from `feature` to `main`.
3. Merge the Pull Request.
4. Pull the updated main branch locally:
```bash
git checkout main
git pull origin main
```

For Pages:
Repository → Settings → Pages → Deploy from branch → `main` → `/ (root)` → Save.
