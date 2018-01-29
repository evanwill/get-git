---
title: 5-More
nav: true
---
# More Stuff

The basic workflow is everything you need to version control your work in personal repositories.
Of course, things get more complex when collaborating with a team or contributing to a project.
Workflow strategies (Github flow, Gitflow, feature branch, etc)
There is LOTS more to learn about Git!

Here are a few suggestions for the next topics to master:

## GitHub Fork

Forking is a GitHub concept.
It allows you to create a new copy of a repository, yet maintain a connection so that changes can be exchanged between them via "pull requests" (PR).

- Go to the [gitworkshop repository](https://github.com/uidaholib/gitworkshop).
- Click the "Fork" button in the upper right.
- Add a new file with your name and profile url.
- Click "New pull request" to send me a message asking to add your edits to the main repository.

## git branch

[Branching](https://git-scm.com/book/en/v2/Git-Branching-Branches-in-a-Nutshell) is a Git fundamental that allows you to test out ideas in parallel to your main repository without disrupting the master copy. 

```
git branch newbranch 
git checkout newbranch
git checkout -b new2
git branch --list
git branch -D newbranch
```

## git merge 

Once you have branches, you will want to `merge` them together.

```
git checkout -b new3
echo "new stuff" > newfile.txt
git add newfile.txt
git commit -m "new stuff"

git checkout master
git merge new3
git branch -D new3
```

## .gitignore

Create a `.gitignore` file in the repository to tell Git to ignore things.

## GUI 

There are a variety of [GUI apps available](https://git-scm.com/downloads/guis) for managing and visualizing Git repositories.
However, one of the most handy methods is to use a good text editor with Git support built in. 

- [Atom](https://atom.io/)
- [Visual Studio Code](https://code.visualstudio.com/)

# gh-pages

GitHub pages is a quick and easy way to host static web pages. 
It is enabled from the "Settings" for a repository.
There is three options:

- add static HTML files
- use the "Automatic page generator"
- use Jekyll build service

Once published your website will be [username].github.io/[repositoryname]

For example, https://uidaholib.github.io/get-git/
