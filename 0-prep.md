---
title: 0-Prep
nav: true
---

# Prep and Installation 

To join the wonderful world of version control, please create a GitHub account and install Git on your system.

## 1. Get a GitHub Account

[GitHub](https://github.com/){:target="_blank" rel="noopener"} is a Git repository hosting service, a place to store and sync your work in the cloud. 

Visit <https://github.com> and sign up for a free account. 
Be sure to verify your email to get all features activated!

When signing up, think a bit about which email address and user name you want to use--especially if you will be doing professional work on the platform.

Your email and user name will be recorded with every commit.
This helps ensure integrity and authenticity of the history.
Most people keep their email public. 
Alternatively, check GitHub's tips on how to [set up email privacy](https://help.github.com/en/github/setting-up-and-managing-your-github-user-account/setting-your-commit-email-address#about-commit-email-addresses){:target="_blank" rel="noopener"}. 
GitHub can provide a no-reply email address that can be found via your email settings on your profile.

## 2. Install Git

Installing this free and open source software is pretty straightforward:

**Windows:** 

- Install [Git for Windows](https://git-scm.com/downloads){:target="_blank" rel="noopener"} using the default options, *except* when setup asks you to choose the default editor used by Git, select "Use the Nano editor by default". This will give you Git, Git Bash, and Git GUI. Git Bash is a terminal that lets you use UNIX style commands and utilities on Windows.

**Mac:** 

- Mac systems will require the "Xcode Command Line Tools" installed, so open a terminal (to find your terminal search for "terminal" in your Spotlight), type in the command `xcode-select --install`, and follow the prompts. After the install finishes, try typing `git --version`. If you want a newer version of Git, download the official [Mac git installer](https://git-scm.com/downloads){:target="_blank" rel="noopener"}.

**Linux:** 

- Install from your distribution's software center or package manager (for Ubuntu `sudo apt install git`).

## *Optional Stuff:*

### Text Editor 

When working with code you should have a good text editor.
Windows notepad does not handle UTF-8 encoding or UNIX line endings that are standard for most cross platform applications. 
For basic editing, Windows [Notepad++](https://notepad-plus-plus.org/){:target="_blank" rel="noopener"}, Mac TextEdit, or Linux Gedit are sufficient.
However, a more complete code editor will be helpful for working on projects and can often integrate with Git to make your life easier.

Open-source cross platform suggestions:

- [Visual Studio Code](https://code.visualstudio.com/){:target="_blank" rel="noopener"}
- [Atom](https://atom.io/){:target="_blank" rel="noopener"}

### Git GUIs

This workshop introduces the basic Git workflow using the command line and GitHub web interface. 
However, you may prefer a GUI application for your future day-to-day work with Git.
There are a variety of [GUI apps available](https://git-scm.com/downloads/guis){:target="_blank" rel="noopener"} for managing and visualizing Git repositories, including "git-gui" that is built in to every default Git install.

If you are interested in using a simple visual app integrated with GitHub, Windows and Mac users should install [GitHub Desktop](https://desktop.github.com/){:target="_blank" rel="noopener"} using the default options.
A more powerful alternative is [SourceTree](https://www.sourcetreeapp.com/){:target="_blank" rel="noopener"} from Atlassian / [BitBucket](https://bitbucket.org/){:target="_blank" rel="noopener"}.
On Linux [gitg](https://wiki.gnome.org/Apps/Gitg/){:target="_blank" rel="noopener"} and [GitKraken](https://www.gitkraken.com/){:target="_blank" rel="noopener"} are good options.

However, many users will find they complete most Git commands using integrations built into their text editors such as VS Code or Atom instead.
