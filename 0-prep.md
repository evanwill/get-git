---
title: 0-Prep
nav: true
---

# Prep and Installation 

To join the wonderful world of version control, please create a GitHub account and install Git on your system.

## 1. Get a GitHub Account

[GitHub](https://github.com/){:target="_blank"} is a Git repository hosting service, a place to store and sync your work in the cloud. 
Take a minute to create a [free account](https://github.com/join){:target="_blank"}.
They provide some great introductory [tutorials](https://guides.github.com/){:target="_blank"}, but you can probably ignore them if you are coming to the workshop!

## 2. Install Git

Git is a version control system, a piece of software on your computer. 
Installing it is pretty easy:

- Windows: install [Git for Windows](https://git-for-windows.github.io/){:target="_blank"} using the default options. When setup asks you to choose the default editor used by Git, select "Use the Nano editor by default". This will give you Git, Git Bash, and Git GUI. Git Bash is a great terminal that lets you use UNIX style commands and utilities on Windows. *Note:* if you have issues with needing admin privileges to install, please download the Full version of [cmder](http://cmder.net/) instead, which includes a portable version of Git for Windows.
- Mac: check if Git is already installed by opening terminal and typing `git --version`. If you do not have it, download the official [Mac installer](https://git-scm.com/downloads){:target="_blank"}.
- Linux: install from your distribution's software center or package manager (for Ubuntu `sudo apt-get install git`).

## *Optional Stuff:*

### Text Editor 

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for most cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/){:target="_blank"}, Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for working on projects and can often integrate with Git to make your life easier.

Open-source cross platform suggestions:
- [Visual Studio Code](https://code.visualstudio.com/){:target="_blank"}
- [Atom](https://atom.io/){:target="_blank"}

### Git GUIs

This workshop introduces the basic Git workflow using the command line and GitHub web interface. 
However, you may prefer a GUI application for your future day-to-day work with Git.
There are a variety of [GUI apps available](https://git-scm.com/downloads/guis){:target="_blank"} for managing and visualizing Git repositories.

If you are interested in using a simple visual app integrated with GitHub, Windows and Mac users should install [GitHub Desktop](https://desktop.github.com/){:target="_blank"} using the default options.
A more powerful alternative is [SourceTree](https://www.sourcetreeapp.com/){:target="_blank"} from Atlassian / [BitBucket](https://bitbucket.org/){:target="_blank"}.
On Linux [gitg](https://wiki.gnome.org/Apps/Gitg/){:target="_blank"} and [GitKraken](https://www.gitkraken.com/){:target="_blank"} are good options.
