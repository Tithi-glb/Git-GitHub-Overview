# Git and GitHub Overview

A comprehensive guide to understanding **Git** and **GitHub**, including their concepts, features, architecture, workflows, and commonly used commands.

---

## Table of Contents

- [Introduction](#introduction)
- [What is Git?](#what-is-git)
- [What is GitHub?](#what-is-github)
- [Git vs GitHub](#git-vs-github)
- [Git Features](#git-features)
- [GitHub Features](#github-features)
- [Basic Git Commands](#basic-git-commands)


---

# Introduction

Git and GitHub are essential tools used in modern software development.

- **Git** is a distributed version control system that tracks changes in source code.
- **GitHub** is a cloud-based platform that hosts Git repositories and provides collaboration tools.

Together, they help developers manage code, collaborate with teams, and maintain project history.

---

# What is Git?

Git is an open-source distributed version control system used to track changes in files and manage software development projects.

Git allows developers to:

- Track changes in code
- Restore previous versions
- Create branches
- Merge different versions
- Collaborate with other developers
- Maintain project history

Git works locally on your computer, so most operations can be performed without an internet connection.

---

# What is GitHub?

GitHub is an online platform that hosts Git repositories and provides collaboration features.

GitHub helps developers:

- Store projects online
- Share code
- Review changes
- Manage issues
- Collaborate with teams
- Automate development workflows

GitHub uses Git as its version control engine.

---

# Git vs GitHub

| Git | GitHub |
|---|---|
| Version control system | Code hosting platform |
| Works locally | Works online |
| Tracks code changes | Hosts Git repositories |
| Created by Linus Torvalds | Owned by Microsoft |
| Uses commands | Provides graphical interface |


# Git Features

- **Version Control** - Track and manage changes in code over time.
- **Distributed System** - Work locally without requiring an internet connection.
- **Branching** - Create separate branches for different features or changes.
- **Merging** - Combine changes from multiple branches.
- **Commit History** - Maintain a complete record of project changes.
- **Collaboration** - Allow multiple developers to work on the same project.
- **Stashing** - Temporarily save unfinished changes.
- **Conflict Resolution** - Identify and help resolve code conflicts.
- **Reverting Changes** - Restore previous versions of code.
- **Fast Performance** - Execute operations quickly with local repositories.

# GitHub Features

- **Repository Hosting** - Store and manage Git repositories online.
- **Pull Requests** - Review and merge code changes.
- **Code Review** - Collaborate and improve code quality.
- **Issues** - Track bugs, tasks, and feature requests.
- **Branching** - Create separate versions for development.
- **GitHub Actions** - Automate testing, building, and deployment.
- **Forks** - Copy repositories for modification and contribution.
- **Project Management** - Manage tasks using boards and milestones.
- **Security** - Detect vulnerabilities and protect code.
- **GitHub Pages** - Host static websites from repositories.
- **Releases** - Manage software versions and updates.
- **Collaboration** - Work with teams and open-source communities.

# Basic Git Commands

# Git Commands Cheat Sheet

| Command | Description |
|---|---|
| `ls -a` | Show all files including hidden files. |
| `ls foldername` | Show the contents inside a specific folder. |
| `touch filename.txt` | Create a new file. |
| `cat filename` | Display the contents of a file. |
| `git init` | Initialize an empty Git repository where all changes will be stored. |
| `git status` | Show pending changes, tracked files, and untracked files. |
| `git add filename` | Add a specific file to the staging area. |
| `git add .` | Add all files to the staging area. |
| `git commit -m "message"` | Commit staged changes with a message. |
| `git restore filename` | Discard changes made to a file. |
| `git restore --staged filename` | Remove a file from the staging area. |
| `git log` | Display all commits. |
| `git log --oneline` | Display commits in a short format. |
| `git log --graph --oneline --all` | Show a graph view of all commits and branches. |
| `rm -rf filename` | Delete a file or directory. |
| `git reset commit-no` | Remove commits after the specified commit and move changes back to the unstaged area. |
| `git stash` | Temporarily save uncommitted changes. |
| `git stash pop` | Restore the latest stashed changes. |
| `git stash clear` | Remove all saved stash changes. |
| `git remote add origin url` | Connect local repository to a remote repository (GitHub). |
| `git remote -v` | Display all remote URLs connected to the repository. |
| `git push origin main` | Push local commits to the remote main branch. |
| `git branch branchname` | Create a new branch. |
| `git checkout branchname` | Switch the HEAD pointer to another branch. |
| `git merge branchname` | Merge another branch into the current branch. |
| `git switch branch-name` | Switch to an existing branch. |
| `git switch -c branch-name` | Create and switch to a new branch. |
| `git branch -d branch-name` | Delete a branch only if it has been merged. |
| `git branch -D branch-name` | Force delete a branch. |
| `git branch -m new-name` | Rename the current branch. |
| `git branch -m old-name new-name` | Rename another branch. |
| `git branch -a` | Show all local and remote branches. |
| `git branch -r` | Show only remote branches. |
| `git fetch` | Download changes from remote without merging. |
| `git pull` | Download and merge the latest changes. |
| `git pull origin main` | Pull latest changes from the main branch. |
| `git clone url` | Copy a remote repository to your local machine. |
| `git remote add upstream url` | Add an upstream repository URL. |
