# DevOps Git Task – Task 4

## Objective
Manage a DevOps project using Git best practices like branching, pull requests, commits, tags, and documentation.

---

## Tools Used
- Git (Version Control)
- GitHub (Remote Repository Hosting)

---

## Branches Used
- `main` – Final production code
- `dev` – Development branch for integration
- `feature-1` – Feature branch for new changes

---

## Git Workflow Followed
1. Initialized Git in local folder
2. Created `.gitignore`, `README.md`, and a sample `main.py` file
3. Connected local repo to GitHub
4. Created and switched to `dev` and `feature-1` branches
5. Made code changes in `feature-1` and pushed to GitHub
6. Created Pull Requests:
   - Merged `feature-1` → `dev`
   - Merged `dev` → `main`
7. Created a Git tag `v1.0` for final version

---

## Files Included
- `main.py`: Sample Python file with simple print statements
- `.gitignore`: To ignore unnecessary files (e.g., `.env`, `node_modules`, `.log` files)
- `README.md`: Project documentation (this file)

---

## Git Tag
- **v1.0** – First working version pushed to `main` branch

---

## Git Commands Used

```bash
git init
git add .
git commit -m "message"
git branch -M main
git remote add origin <repo-url>
git push -u origin main
git checkout -b dev
git checkout -b feature-1
git merge
git tag -a v1.0 -m "First stable version"
git push origin v1.0
