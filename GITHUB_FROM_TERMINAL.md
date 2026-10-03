# GitHub From the Terminal

This guide shows a simple terminal-based Git workflow.

## 1. Go to your project

Example:

```cmd
cd Documents
cd TerminalPractice
```

## 2. Initialize Git

```cmd
git init
```

## 3. Check the repository

```cmd
git status
```

## 4. Add your files

```cmd
git add .
```

## 5. Commit

```cmd
git commit -m "Create terminal learning project"
```

## 6. Create a repository on GitHub

Create an empty repository on GitHub. Then copy its HTTPS repository address.

Example format:

```text
https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Do not use someone else's URL.

## 7. Connect local Git to GitHub

```cmd
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

## 8. Push

```cmd
git branch -M main
git push -u origin main
```

After this, refresh your GitHub repository and your files should appear.

## Later updates

When you change your project:

```cmd
git status
git add .
git commit -m "Update terminal notes"
git push
```
