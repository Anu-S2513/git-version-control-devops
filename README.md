# Git Version-Controlled DevOps Project

## Task 4 - Git Version Control

This project demonstrates Git and GitHub version-control best practices.

## Objectives

- Initialize a Git repository
- Create and manage branches
- Create commits
- Use Pull Requests
- Merge branches
- Use .gitignore
- Create Git tags
- Document the project using Markdown

## Technologies Used

- Git
- GitHub
- Markdown
- Visual Studio Code
- PowerShell

## Branching Workflow

The project uses three types of branches:

- main: Contains the stable version of the project.
- dev: Used for development work.
- feature/git-documentation: Used to develop a specific feature.

### Workflow Diagram

feature/git-documentation
          |
          | Pull Request
          v
         dev
          |
          | Pull Request
          v
         main

## Git Commands Used

### Initialize Repository

git init

### Check Status

git status

### Create a Branch

git checkout -b dev

### Stage Changes

git add .

### Commit Changes

git commit -m "Describe your changes"

### Push Changes

git push

### Create a Git Tag

git tag -a v1.0.0 -m "First version of Git DevOps project"

### Push the Tag

git push origin v1.0.0

## Pull Requests

Pull Requests were used to merge:

1. feature/git-documentation into dev
2. dev into main

## .gitignore

The .gitignore file excludes unnecessary files from Git tracking.

Examples:
- Thumbs.db
- Desktop.ini
- .vscode/
- *.log

## Git Tag

Version: v1.0.0

The tag identifies the first version of this project.

## Learning Outcomes

- Understanding Git version control
- Working with multiple branches
- Creating commits
- Using Pull Requests
- Merging branches
- Ignoring unnecessary files
- Creating version tags
- Maintaining project documentation

## Conclusion

This project demonstrates a basic Git and GitHub workflow for managing a version-controlled DevOps project.