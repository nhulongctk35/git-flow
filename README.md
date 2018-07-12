# git-flow
Hi Falcon team, I define this simple git flow to help you guys easily when working with git

## Before starting working on new feature
```javascript
git fetch upstream
```

## Create new brnach
```javascript
git checkout -b feature-name upstream/dev
```

## Add changes
```javascript
git add .
```

## Pick file changes
```javascript
git add file_url
```

## Commit changes
```javascript
git commit -m "[BOOST-ID]:Task ..."
```

## Push code to fork repository
```
git push origin feature-name
```

## Create pull request from fork repository to origin repository

## Some commons command

### Show remote links
First, let's see a list of the repositories (remotes) whose branches you track:

```javascript
git remote -v
```

### Switching Branches
First, you'll want to know what branches are available in your working directory:

```javascript
git branch
```

Now, you can easily switch between branches with git checkout:

```javascript
git checkout branch-name
```

### Status
```javascript
git status
```

### Rebasing
```javascript
git fetch upstream
git rebase upstream/dev
```

### Undoing Commits
The following command will undo your most recent commit and put those changes back into staging, so you don't lose any work:
```javascript
git reset --hard HEAD~1
```

### Stashing
Sometimes you need to stash your changes so you can be on a clean branch or maybe because you want to go back and try something before you make a commit with these changes. Here's how you do a stash:
```javascript
git stash
```

Apply stash

```javascript
git stash apply
```



