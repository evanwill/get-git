---
title: 4-History
nav: true
---
# History

So `commit` stores away all this history, what can we do with it?

## git log

Check how far we have come! 
Take a look at the repository's history of commits:

```
git log

git log --oneline
```

## git diff

We can compare files with the history.
Modify one of the file in your repository using a text editor or the command line.

```
echo "more important notes!" >> notes.txt

git status

git diff

git diff notes.txt

git add notes.txt

git diff

git commit -m "testing diff"

git diff
```

Diff allows us to see what changes were made to the currently unstaged files. 
It's best to check this before you commit to ensure you know what you are changing.
Many text editors have a diff visualization built in, which is very handy!

## git checkout

Wait that last commit was no good! How can we undo?

Let's get the earlier version back with `checkout`.
You can track individual commits using their id given by `git log`. 
Or we can refer to them sequentially. 
The most recent commit is called `HEAD`. 
One back is called `HEAD~1` ("head minus one"), and so on. 
If you `git checkout` a specific file, it will reset it to the specified commit in your working directory.

```
git checkout HEAD~1 notes.txt

git status

git diff HEAD notes.txt

git checkout HEAD notes.txt

git status
```

These two checkouts undid each other!
If you want to undo, remember to `add` and `commit`.

```
git checkout HEAD~1 notes.txt

git status

git add notes.txt

git commit -m "undo notes changes"
```

> if you get 'detached HEAD' warning, type `git checkout master`
