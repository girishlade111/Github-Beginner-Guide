# Getting Started with GitHub

## 📚 Table of Contents
- [What is GitHub?](#what-is-github)
- [Creating Your Account](#creating-your-account)
- [Setting Up Git](#setting-up-git)
- [Your First Repository](#your-first-repository)
- [Basic Workflow](#basic-workflow)

## What is GitHub?

GitHub is a web-based platform for version control and collaboration. It allows developers to:
- Store and manage code
- Track changes and versions
- Collaborate with other developers
- Showcase projects and portfolios
- Contribute to open-source projects

### Key Concepts

**Repository (Repo)**: A storage space for your project containing all files and revision history.

**Commit**: A snapshot of your changes with a descriptive message.

**Branch**: A parallel version of your repository for developing features independently.

**Pull Request (PR)**: A request to merge your changes into another branch.

**Fork**: Your personal copy of someone else's repository.

**Clone**: Downloading a repository to your local machine.

## Creating Your Account

1. Visit [github.com](https://github.com)
2. Click **Sign up**
3. Enter your email, password, and username
4. Verify your account via email
5. Choose your plan (Free is perfect for beginners)

### Profile Setup Tips
- Use a professional username
- Add a profile picture
- Write a brief bio
- Pin your best repositories
- Add your location and website

## Setting Up Git

### Installation

**Windows:**
```bash
# Download from git-scm.com
# Or use chocolatey
choco install git
```

**macOS:**
```bash
# Using Homebrew
brew install git
```

**Linux (Ubuntu/Debian):**
```bash
sudo apt-get update
sudo apt-get install git
```

### Configuration

Set your identity:
```bash
git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"
```

Verify your configuration:
```bash
git config --list
```

### SSH Key Setup (Recommended)

1. Generate SSH key:
```bash
ssh-keygen -t ed25519 -C "your.email@example.com"
```

2. Start SSH agent:
```bash
eval "$(ssh-agent -s)"
```

3. Add your SSH key:
```bash
ssh-add ~/.ssh/id_ed25519
```

4. Copy your public key:
```bash
cat ~/.ssh/id_ed25519.pub
```

5. Add to GitHub:
   - Go to Settings → SSH and GPG keys
   - Click "New SSH key"
   - Paste your key and save

## Your First Repository

### Creating a Repository on GitHub

1. Click the **+** icon in the top right
2. Select **New repository**
3. Choose a repository name
4. Add a description (optional)
5. Choose Public or Private
6. Initialize with README (recommended)
7. Add .gitignore (optional)
8. Choose a license (optional)
9. Click **Create repository**

### Cloning a Repository

```bash
# HTTPS
git clone https://github.com/username/repository.git

# SSH (recommended)
git clone git@github.com:username/repository.git
```

### Creating a Local Repository

```bash
# Create a new directory
mkdir my-project
cd my-project

# Initialize Git
git init

# Create a README
echo "# My Project" >> README.md

# Add and commit
git add README.md
git commit -m "Initial commit"

# Connect to GitHub
git remote add origin git@github.com:username/my-project.git

# Push to GitHub
git branch -M main
git push -u origin main
```

## Basic Workflow

### The Git Workflow

1. **Make changes** to your files
2. **Stage changes** with `git add`
3. **Commit changes** with `git commit`
4. **Push changes** with `git push`

### Essential Commands

```bash
# Check status
git status

# Add files to staging
git add filename.txt        # Specific file
git add .                   # All files
git add *.js               # All JS files

# Commit changes
git commit -m "Descriptive message"

# Push to remote
git push origin main

# Pull latest changes
git pull origin main

# View commit history
git log
git log --oneline          # Compact view

# View differences
git diff                   # Unstaged changes
git diff --staged          # Staged changes
```

### Working with Branches

```bash
# Create a new branch
git branch feature-name

# Switch to a branch
git checkout feature-name

# Create and switch (shortcut)
git checkout -b feature-name

# List all branches
git branch

# Merge a branch
git checkout main
git merge feature-name

# Delete a branch
git branch -d feature-name
```

### Best Practices

✅ **DO:**
- Write clear, descriptive commit messages
- Commit frequently with logical chunks
- Pull before you push
- Use branches for new features
- Review changes before committing

❌ **DON'T:**
- Commit large binary files
- Commit sensitive information (passwords, API keys)
- Use vague commit messages like "fixed stuff"
- Work directly on the main branch
- Force push to shared branches

## Next Steps

- Learn about [GitHub Workflow](./02-github-workflow.md)
- Master [Branching Strategies](./03-branching-strategies.md)
- Explore [Collaboration Tips](./04-collaboration.md)
- Check out [Keyboard Shortcuts](./05-keyboard-shortcuts.md)

## Helpful Resources

- [GitHub Docs](https://docs.github.com)
- [Git Documentation](https://git-scm.com/doc)
- [GitHub Learning Lab](https://lab.github.com)
- [Git Cheat Sheet](https://education.github.com/git-cheat-sheet-education.pdf)

---

**[← Back to Main](../README.md)** | **[Next: GitHub Workflow →](./02-github-workflow.md)**
