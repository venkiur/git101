# Git Basics

Welcome to the **Git Basics** repository! This repository covers all the fundamental concepts and commands required to get started with Git, the popular version control system used by developers worldwide.

---

## 📖 Table of Contents

- [What is Git?](#what-is-git)
- [Installing Git](#installing-git)
- [Basic Git Workflow](#basic-git-workflow)
- [Common Git Commands](#common-git-commands)
- [Branching and Merging](#branching-and-merging)
- [Working with Remote Repositories](#working-with-remote-repositories)
- [Git Ignore](#git-ignore)
- [Undoing Changes](#undoing-changes)
- [Git Best Practices](#git-best-practices)
- [Resources](#resources)

---

## 📘 What is Git?

Git is a distributed version control system that allows multiple developers to collaborate on a project by tracking changes, managing versions, and facilitating teamwork efficiently.

### Why Use Git?
- Track changes over time
- Collaborate with others easily
- Branching and merging for isolated development
- Backup and restore code

---

## 🛠 Installing Git

### Windows:
1. Download Git from the official website: [git-scm.com](https://git-scm.com/)
2. Install using the downloaded installer
3. Verify installation by running:
   ```bash
   git --version
   ```

### macOS:
```bash
brew install git
```

### Linux:
```bash
sudo apt update
sudo apt install git
```

---

## 🔄 Basic Git Workflow

1. **Initialize a repository:**
   ```bash
   git init
   ```

2. **Add files to staging area:**
   ```bash
   git add <filename>
   ```

3. **Commit changes:**
   ```bash
   git commit -m "Initial commit"
   ```

4. **Push to remote repository:**
   ```bash
   git push origin main
   ```

---

## 🔧 Common Git Commands

| Command | Description |
|---------|-------------|
| `git init` | Initialize a new repository |
| `git clone <url>` | Clone an existing repository |
| `git status` | Check the status of changes |
| `git add <file>` | Stage changes |
| `git commit -m "message"` | Commit staged changes |
| `git log` | View commit history |
| `git push origin <branch>` | Push changes to remote |
| `git pull origin <branch>` | Pull changes from remote |
| `git diff` | Show changes |

---

## 🌿 Branching and Merging

### Create a new branch:
```bash
git branch feature-branch
```

### Switch to the branch:
```bash
git checkout feature-branch
```

### Merge branches:
```bash
git merge feature-branch
```

### Delete a branch:
```bash
git branch -d feature-branch
```

---

## 🌍 Working with Remote Repositories

### Connect to a remote repository:
```bash
git remote add origin <repository-url>
```

### Push local changes:
```bash
git push origin main
```

### Pull latest changes:
```bash
git pull origin main
```

---


---

## 🔄 Undoing Changes

### Unstage changes:
```bash
git reset <file>
```

### Undo last commit:
```bash
git reset --soft HEAD~1
```

### Discard changes:
```bash
git checkout -- <file>
```

---

## ✅ Git Best Practices

- Commit often with meaningful messages.
- Use branches for new features.
- Pull before pushing to avoid conflicts.
- Keep the repository clean.
- Regularly review and refactor code.

---

## 📚 Resources

- [Official Git Documentation](https://git-scm.com/doc)
- [Pro Git Book](https://git-scm.com/book/en/v2)

---

## 🏁 Conclusion

This repository provides a solid foundation for getting started with Git. Explore and practice these commands to become proficient in version control.

Happy coding! 🚀

