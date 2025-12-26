# Hardware Library
- Developer: Trần Nguyên Hiền
- Major: Electronics and Communication Engineering
- School: CAN THO UNIVERSITY
- Email: trannguyenhien29085@gmail.com
-----------------------------------------------------
### Introduction
This repository contains hardware libraries that I have created for use in applications. 
Most of them include hardware libraries written in both C and C++, along with examples of how 
to use the libraries. Furthermore, this repository also contains several standalone applications.

### Improvements and changes:
Join me in developing the Hardware Library Repository. Let's find solutions to further optimize this library.

### Bugs and issues
For library errors, please create an issue on GitHub as it makes it easier for me to track. If possible, provide a minimal code snippet to clearly show the error or problem. Add information about the platform used and version, etc.

------------------------------------------------- Installation instructions -------------------------------------------------
```
git clone https://github.com/NguyenHien-8/Hardware-Library.git
```
### 1.Windows
**The command automatically creates directories for all branches**
- On PowerShell
```
git branch -r | % { $n = $_.Trim() -replace 'origin/'; if($n -notmatch 'HEAD'){ git worktree add $n $n } }
```
- On CMD
```
for /f "tokens=1,* delims=/" %a in ('git branch -r ^| findstr /v "HEAD"') do git worktree add "%b" "origin/%b"
```

### 2.Linux
**The command automatically creates directories for all branches.**
- On Bash
```
git branch -r | grep -v 'HEAD' | cut -d/ -f2- | xargs -I{} git worktree add {} origin/{}
```

### 3.MacOS
**The command automatically creates directories for all branches.**
- On Zsh/Bash
```
git branch -r | grep -v 'HEAD' | cut -d/ -f2- | xargs -I{} git worktree add {} origin/{}
```

Thank you,

Regards,
NguyenHien