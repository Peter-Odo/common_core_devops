<!-- What is Version Control -->

# Version Control

### Version control is a system that allows engineers to track and manage changes to a source (software) code over time.

## Core concepts

- Snapshots of project
- Collaboration
- Change Tracking

## Why it's Important

- Enables seamless collaboration in large teams
- Ensures a reliable history of changes
- Protects against data loss by storing project in remote repositories

<!-- Benefits of Git -->

- Decentralized nature
- Performance
- Features: Branching, Pull Request, Merge
- Support for Automation

<!-- Basic of Git -->

### Linux:

```
sudo apt-get install git
```

### Mac:

```
brew install git
```

### Windows:

```
https://git-scm.com
```

### Core commands

- Initializing a repository (folder)

```
git init
```

- Check repository (folder) status

```
git status
```

- Stage changes

```
git add <file_name> # git add index.js
git add .           # stage all changes
```

- Commit Changes

```
git commit -m 'Describe your changes'
```

- Push changes: upload local repository(folder) to remote provider (GitHub)

```
git push origin <branch_name>
```

### Not-so Core commands

- Create a new branch

```
git branch <branch_name> || git checkout -b <branch_name>
```
