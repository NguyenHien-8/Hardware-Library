# Hardware Library
### Developer: Trần Nguyên Hiền
### Major: Electronics and Communication Engineering
### School: CAN THO UNIVERSITY
### Email:  [trannguyenhien29085@gmail.com]
----------------------------------------------------
### Introduction
This repository contains hardware libraries that I have created for use in applications. 
Most of them include hardware libraries written in both C and C++, along with examples of how 
to use the libraries. Furthermore, this repository also contains several standalone applications.

### Improvements and changes:
Join me in developing the Hardware Library Repository. Let's find solutions to further optimize this library.

### Bugs and issues
For library errors, please create an issue on GitHub as it makes it easier for me to track. If possible, provide a minimal code snippet to clearly show the error or problem. Add information about the platform used and version, etc.

------------------------- Installation instructions -------------------------

### Windows

```
git branch -r | % { $n = $_.Trim() -replace 'origin/'; if($n -notmatch 'HEAD'){ git worktree add $n $n } }
```