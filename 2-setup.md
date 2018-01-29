---
title: 2-Setup
nav: true
---

# First Time Setup and Configuration

To start learning Git we will use it on the command line.
Although there are GUI clients to manage Git repositories, being familiar with the command line version will help you better understand the basic workflow.
If you need a command line refresher, check out this [mini-lesson](https://evanwill.github.io/_drafts/notes/commandline.html).
So fire up your favorite shell, terminal, or Git Bash to get started!

## GitHub web interface

demo the basic features of git using github interface
Forking is a GitHub concept.
It allows you to create a new copy of a repository, yet maintain a connection so that changes can be exchanged between them via "pull requests" (PR).

- Go to the [gitworkshop repository](https://github.com/uidaholib/gitworkshop).
- Click the "Fork" button in the upper right.

fork
look at history
edit
commit

## Create repository on GitHub

A more common workflow is to create or fork a repository on GitHub, then `clone` it to your local machine.
GitHub acts as Git in your browser, with added benefits.
Create a new remote repository:

- Login to [GitHub](https://github.com/) 
- Click the plus sign on the upper right and select "New repository" from the drop down
- Give it a nice name
- Check "Initialize this repository with a README"
- Click "Create repository"

With this test repository ready, we can move on to the basic Git workflow!

## Git Config

Some initial setup is necessary the first time you use Git on a computer.
You will use these commands only once, unless you want to change something.

Set your name and email:

```
git config --global user.name "Evan Will"
git config --global user.email "myemail@gmail.com"
```

> Your email and user name is recorded with every commit.
> This helps ensure integrity and authenticity of the history.
> Most people keep their email public, but if you are concerned about privacy, check GitHub's tips to [hide your email](https://help.github.com/articles/keeping-your-email-address-private/).

Set your default text editor (Windows "notepad", Mac "edit -w", Linux "nano -w"):

```
git config --global core.editor "notepad"
```

> Git opens the default editor to ask for commit messages. 
> You are most likely to encounter it when merging.
> If you don't set a default editor, Git will use the default default--which might be surprising if you are not used to terminal-based editors. 
> The default default on Windows is [VIM](http://www.vim.org/). 
> If you are stuck in VIM and can't figure out how to escape, type `:wq` to save and quit ([quick ref](https://w3.cs.jmu.edu/bernstdh/Web/common/help/vim.php) and don't worry, you are [not alone in confusion](https://stackoverflow.blog/2017/05/23/stack-overflow-helping-one-million-developers-exit-vim/)).

## Create repository locally

To try Git out, create a local repository:

```
mkdir test

cd test

git init
```

Your new directory `test` will have a hidden `.git` directory which will contain the full history. 
It is hidden for a reason--you don't need to know anything about it!
If you want to add this repository to GitHub, you have to `git remote add`.
