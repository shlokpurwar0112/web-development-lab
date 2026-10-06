# Web Development Lab – Experiments 1 to 6

This repository contains the six weekly web development experiments.

## Structure
- `week1-github/` – Git/GitHub workflow notes and branch/merge practice
- `week2-portfolio/` – Personal portfolio using HTML and CSS
- `week3-todo/` – Dynamic To-Do List using JavaScript and DOM
- `week4-seo-accessibility/` – SEO and accessibility optimized webpage
- `week5-weather/` – Weather app using Fetch API and Open-Meteo
- `week6-responsive-blog/` – Responsive blog using Bootstrap and media queries

## Run locally
Open `index.html` in a browser, or use VS Code Live Server.

## Git commands for Experiment 1
```bash
git init
git add .
git commit -m "Initial commit"
git branch -M main
git remote add origin YOUR_GITHUB_REPOSITORY_URL
git push -u origin main

git checkout -b feature
git add .
git commit -m "Add feature changes"
git push -u origin feature
```

Create a Pull Request on GitHub from `feature` to `main`, merge it, then:
```bash
git checkout main
git pull origin main
```

## GitHub Pages
For a repository containing these folders, go to:
Settings → Pages → Deploy from a branch → `main` → `/ (root)` → Save.

The root `index.html` acts as the lab homepage.
