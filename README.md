"# github-3.1-soon" 

# 10 Git Commands Every Developer Should Know

## 1. Git clone

```sh
git clone <https://name-of-the-repository-link>
```

## 2. Git branch

### 2.1 Create a new branch

```sh
git branch <branch-name>
```

### 2.2 List the branch(es)

```sh
git branch or git branch --list
```

### 2.3 Delete a branch

```sh
git branch -d <branch-name>
```

## 3. Git checkout

### 3.1 Switch from one branch to another

```sh
git checkout <name-of-your-branch>
```

### 3.2 Create a new branch and switch to it

```sh
git checkout -b <name-of-your-branch>
```

## 4. Git status

```sh
git status
```

## 5. Git add

```sh
git add <file>
```

## 6. Git commit

```sh
git commit -m "commit message"
```

## 7. Git push

```sh
git push <remote> <branch-name>
```

## 8. Git pull

```sh
git pull <remote>
```

## 9. Git revert

```sh
git revert <commit hash>
```

## 10. Git merge

To merge the changes in feature branch to dev branch:

First you should switch to the dev branch:

```sh
git checkout dev
```

Before merging, you should update your local dev branch:

```sh
git fetch
```

Finally, you can merge your feature branch into dev:

```sh
git merge feature
```

