# Git LFS

This repository uses **Git LFS(Large File Storage)** to efficiently manage large binary files (such as images, datasets, graphics, or other non-text assets).

## Pre-requisites
- Git **version 18.2 or later**
- **Git LFS** installed

## Repository Structure
git_assignment_HeroVired/LFS
<br>├── iTunes and Git.zip  # Large Binary file
<br>├── README.md           # Project documentation
<br>├── .gitattributes      # It file contains patterns and associated attributes
<br>└── .git/               # Git version control

## Installation
for Windows OS, Download and install from
```
https://git-lfs.com
```
## Initialize Git LFS  
```
git lfs install
```
verify installation
```
git lfs --version
```

## Tracking Binary Files
```
git lfs track "*.zip"
```
These commands add patterns for Git LFS to .gitattributes.
Commit .gitattributes after tracking new types!

```
git add .gitattributes
git commit -m "Track binary file with Git LFS"
```
## Adding and Committing Large Files
1. Add files as usual
```
git add path/<fileame> or git add . (if the file is present in the same folder)
````
2. Commit
```
git commit -m "Add large binary file"
```
3. Push to remote
```
git push origin <branch>
```
On first push of a large file, LFS will upload file contents to the remote server.

## License
This assignment project has no formal license, however, it is part of Hero Vired Git and GitHub Assignment
