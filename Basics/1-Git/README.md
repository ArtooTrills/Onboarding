# Git Basics

## Basic Concept

* https://www.atlassian.com/git/tutorials/setting-up-a-repository

## Developer Workflow
	* Branches
	* Pull Request
	* Code Review
	* Travis / Build Tool

## Remote
```
git remote -v
```

```
git remote add origin ...
```

## Committing

```
git add
```

```
git add -A
```

```
git commit -m ""
```

```
git commit -am ""
```

Push code to remote repo. Use SSH and not HTTPS - https://help.github.com/articles/generating-ssh-keys/

## Handling conflicts

```
git diff
```

```
git checkout --theirs
git checkout --ours
```

```
git reset --hard
```

## Rewriting History

## Tagged releases

```
git tag -a ... 
```

## Stash

```
git stash
```
```
git apply
```
