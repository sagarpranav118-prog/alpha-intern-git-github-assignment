# Git & GitHub Assignment

## 1. Git Version

Command Used:

git --version

Output:
git version 2.54.0.windows.1

---

## 2. Git Configuration

Commands Used:

git config --global user.name "Pranav Sagar"

git config --global user.email "sagarpranav118@gmail.com"

---

## 3. Git vs GitHub

### Git
- Distributed Version Control System
- Works locally on a computer
- Tracks file changes

### GitHub
- Cloud-based hosting platform
- Stores Git repositories online
- Enables collaboration among developers

## Assignment Progress

- Git installed successfully
- Repository created successfully
- First commit completed

## Branch Rename

Command Used:

git branch -m feature/day-1-practice feature/day-1-renamed

## Merge Conflict Practice

A merge conflict occurred because the same line in README.md was modified differently in the main branch and the conflict-practice branch.

Git could not automatically decide which version to keep, so it marked the conflict inside the file.

The conflict was resolved manually by editing README.md, removing the conflict markers, keeping the desired content, and then completing the merge with a commit.

## Commit History

Output of:

git log --oneline

832c966 (HEAD -> main) Completed Day 1 assignment documentation
91e716a Resolved merge conflict in README
5b73097 Modified README on main branch
e4a7d99 (conflict-practice) Modified README on conflict branch
b094e8b (feature/day-1-renamed) Added day 1 practice notes
b26a724 Updated assignment progress
04ca52d Updated README with assignment information
3dd3ae5 (origin/main) Initial project setup

## Branches Created

1. feature/day-1-practice
2. feature/day-1-renamed
3. conflict-practice

## Tags

Command Used:

git tag

Output:

day2-v1