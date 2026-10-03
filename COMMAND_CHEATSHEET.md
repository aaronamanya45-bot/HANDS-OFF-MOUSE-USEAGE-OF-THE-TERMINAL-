# Terminal Cheat Sheet

## Navigation

| Command | Meaning |
|---|---|
| `cd` | Show current directory in CMD |
| `cd folder` | Enter a folder |
| `cd ..` | Go back one folder |
| `dir` | List files/folders in CMD |
| `Get-Location` | Show location in PowerShell |
| `Get-ChildItem` | List items in PowerShell |

## Files and folders

| Command | Purpose |
|---|---|
| `mkdir Name` | Create a folder |
| `type nul > file.txt` | Create an empty file in CMD |
| `New-Item file.txt` | Create a file in PowerShell |
| `del file.txt` | Delete a file in CMD |
| `Remove-Item file.txt` | Delete a file in PowerShell |
| `cls` | Clear CMD screen |

## Git

```text
git init
git status
git add .
git commit -m "message"
git branch -M main
git remote add origin REPOSITORY_URL
git push -u origin main
```

## Networking

```text
ipconfig
ping google.com
tracert google.com
```

## Remember

- `cd` = change directory
- `dir` = list directory contents
- `mkdir` = make directory
- `del` = delete
- `git status` = see what Git thinks has changed
- `git add .` = stage all changes
- `git commit` = save a version in Git
- `git push` = send commits to a remote repository
