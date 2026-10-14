# LAB2

## 1. Create a Repository and Make the First Commit

```bash
mkdir LAB2
touch index.html
git add .
git commit -m "intial commt"
```

## 2. Branching, Commits, Merging, and Pushing

```bash
git branch test
git branch dev
git switch dev
touch style.css
git add .
git commit -m "add syle"
git switch test
touch script.js
git add .
git commit -m "add script"
git switch main
git merge test
git merge dev
git push -u upstream main
```

## 3. Remove a Remote Branch and a Local Branch

**Remove a remote branch:**

```bash
git push origin :branch_name
```

**Remove a local branch:**

```bash
git branch -d branch_name
```

## 4. Get Stash

```bash
git stash
```

## 5. Create and Push Tags

```bash
git tag -a v1.7 -m "version 1.7"
git push origin
git push --tags
git tag
```

## 6. Delete a Remote Tag and a Local Tag

**Delete a remote tag:**

```bash
git push origin --delete v1.7
```

**Delete a local tag:**

```bash
git tag -d v1.7
```

## 7. Download an Image and Add Its Path to README

Download an image and put its path into `README.md`.


![alt text](img.jpg)

