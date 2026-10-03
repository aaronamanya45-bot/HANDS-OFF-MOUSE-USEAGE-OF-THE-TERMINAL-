# Terminal First: Using the Command Line

Welcome to my **Terminal First** learning project.

This project is about learning how to use a computer through the **terminal / command prompt** instead of depending only on the mouse and graphical interfaces.

## Why learn the terminal?

The terminal allows you to control your computer by typing commands. It is useful for:

- Creating, copying, moving and deleting files quickly
- Navigating folders
- Installing software and packages
- Running programs and scripts
- Using Git and GitHub
- Working with programming projects
- Automating repeated tasks
- Troubleshooting computer problems
- Working with servers and remote computers
- Learning skills that are widely used in IT and software development

You do not have to stop using the mouse. The goal is to become comfortable with **both** the graphical interface and the command line.

---

## 1. What is a terminal?

A **terminal** is a text-based interface where we type commands to communicate with the operating system.

On Windows, common command-line tools include:

- **Command Prompt (CMD)**
- **PowerShell**
- **Windows Terminal**

Examples:

```text
C:\Users\Aaron> cd Documents
C:\Users\Aaron\Documents> mkdir MyProject
C:\Users\Aaron\Documents> cd MyProject
```

Instead of opening folders and clicking buttons, we tell the computer what to do.

---

## 2. Important Windows commands

### Show the current folder

CMD:

```cmd
cd
```

PowerShell:

```powershell
Get-Location
```

### List files and folders

CMD:

```cmd
dir
```

PowerShell:

```powershell
Get-ChildItem
```

PowerShell also supports:

```powershell
ls
```

### Move into a folder

```cmd
cd folder_name
```

Example:

```cmd
cd Documents
```

### Move back one folder

```cmd
cd ..
```

### Create a folder

CMD:

```cmd
mkdir MyProject
```

PowerShell:

```powershell
New-Item -ItemType Directory MyProject
```

### Create a file

CMD:

```cmd
type nul > notes.txt
```

PowerShell:

```powershell
New-Item notes.txt
```

### Delete a file

CMD:

```cmd
del notes.txt
```

PowerShell:

```powershell
Remove-Item notes.txt
```

**Be careful when deleting files from the terminal.**

### Clear the screen

CMD:

```cmd
cls
```

PowerShell:

```powershell
Clear-Host
```

---

## 3. A simple terminal practice

Try this step by step:

```cmd
mkdir TerminalPractice
cd TerminalPractice
mkdir Projects
mkdir Notes
type nul > hello.txt
dir
```

You have now created a project folder, two subfolders and a file without opening File Explorer.

---

## 4. Using the terminal with Git

The terminal is extremely useful when working with Git and GitHub.

### Create a Git repository

Inside your project folder:

```cmd
git init
```

### Check the status

```cmd
git status
```

### Add a file

```cmd
git add README.md
```

### Add everything

```cmd
git add .
```

### Create a commit

```cmd
git commit -m "Add terminal learning project"
```

### Connect to a GitHub repository

Replace the URL with your own repository URL:

```cmd
git remote add origin https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

### Push your project

```cmd
git branch -M main
git push -u origin main
```

---

## 5. Terminal vs mouse

| Using the mouse | Using the terminal |
|---|---|
| Open folders manually | `cd` |
| Look through files | `dir` |
| Create a folder with clicks | `mkdir` |
| Delete a file with clicks | `del` |
| Run Git through a GUI | `git` commands |
| Repeat tasks manually | Scripts can automate them |
| Many clicks | A few commands |

The terminal is not necessarily better for every task. It is another powerful way of working.

---

## 6. Why this matters in IT

For an IT student, terminal skills are useful because many technologies are controlled through command-line tools.

Examples include:

- Git and GitHub
- Python
- Node.js
- npm
- MySQL
- Linux
- Docker
- Cloud platforms
- Web servers
- Network tools

Learning the terminal also helps you understand what is happening behind graphical applications.

---

## 7. Useful commands to learn next

After learning the basics, explore:

```text
git
python
pip
npm
node
ssh
ipconfig
ping
tracert
mysql
```

Do not run an unfamiliar command just because you found it online. First understand what it does.

---

## 8. Project challenge

Try to complete these tasks using only the terminal:

1. Create a folder called `MyTerminalProject`.
2. Enter the folder.
3. Create folders called `HTML`, `CSS`, and `JavaScript`.
4. Create a file called `index.html`.
5. List the files and folders.
6. Initialize Git.
7. Check the Git status.
8. Add the files.
9. Make a commit.
10. Push the project to GitHub.

---

## What I learned

This project is evidence that I am practicing command-line skills instead of depending only on graphical interfaces.

The goal is not to avoid the mouse completely. The goal is to understand that a computer can also be controlled efficiently through commands.

---

**Author:** Amanya Aaron  
**Project:** Terminal First Learning Project  
**Focus:** Command Prompt, PowerShell, Git and GitHub
