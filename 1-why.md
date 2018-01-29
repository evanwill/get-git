---
title: 1-Why
nav: true
---

# What is Version Control?

Do you have files like final.txt, final_revised.txt, final_revised2.txt, final_revised2_revised.txt? 

{% include image.html file="phd101212s.gif" alt="final doc comic" caption="'Piled Higher and Deeper' by Jorge Cham <a href='http://www.phdcomics.com/comics/archive.php?comicid=1531' target='_blank'>www.phdcomics.com</a>" width="60%" %}

This is a "local version control system" which depends on your memory and organization to avoid errors and utter confusion.
Automated version control WILL make your life better!

## Why Git?

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed](https://en.wikipedia.org/wiki/Distributed_version_control) version control system.
Rather than storing a series of copies of a file with different filenames, Git captures a snapshot of your project each time you `commit`.
The complete history of your project is safely stored in a hidden `.git` repository.
Everything is recorded with checksums to ensure no information can be lost or corrupted without detection. 
Each commit records the creator, email, and changes made, providing transparency and credit for your project.

{% include image.html file="versions.png" alt="file versions" caption="Adapted from: Software Carpentry, <a href='http://swcarpentry.github.io/git-novice/01-basics/' target='_blank'>Version Control with Git</a>" width="100%" %}

Git is distributed meaning every copy of a repository contains the complete history. 
This is great for collaboration, fast performance, and offline usage.
Git can efficiently branch and automatically merge different sets of changes together, enabling people to work in parallel and sync their files.

{% include image.html file="branch-merge.png" alt="branch and merge versions" caption="Adapted from: Software Carpentry, <a href='http://swcarpentry.github.io/git-novice/01-basics/' target='_blank'>Version Control with Git</a>" width="100%" %}

With Git you can make changes and experiment without fear!
When committing to a repository Git only adds data, it never deletes information. 
This makes almost everything undoable!

## GitHub

Combine it with cloud repository hosting, such as with GitHub, and you have a really useful tool.

## Plain text

code, writing vs. word

## Example Use

Software Carpentry, "Version Control with Git" lesson:

- An [example lesson](https://github.com/swcarpentry/lesson-example) and [template](https://github.com/swcarpentry/styles/) are collaboratively maintained in GitHub repositories.
- Lesson content is created and edited in another [repository](https://github.com/swcarpentry/git-novice).
- Using the template style, the lesson repository generates a [web site](http://swcarpentry.github.io/git-novice/) hosted on Github.
