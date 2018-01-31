---
title: 1-Why
nav: true
---

# What is Version Control?

Do you have files like `final.txt`, `final_revised.txt`, `final_revised2.txt`, `final_revised2_revised.txt`? 

{% include figure.html file="phd101212s.gif" alt="final doc comic" caption="'Piled Higher and Deeper' by Jorge Cham <a href='http://www.phdcomics.com/comics/archive.php?comicid=1531' target='_blank'>www.phdcomics.com</a>" width="60%" %}

This is a "local version control system" which depends on your memory and organization to avoid errors and utter confusion.
Luckily, we have software that can handle this task, from the basic "track changes" to big centralized systems such as [SVN](https://subversion.apache.org/).
Automated version control **WILL** make your life better!

## Why Git?

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html), [distributed version control](https://en.wikipedia.org/wiki/Distributed_version_control) system originally developed for coordinating huge software development projects (specifically the [Linux kernel](https://www.kernel.org/)). 
However, it is fast and flexible enough to be used on any scale project, from your personal notes to your research lab's code--and offers many benefits beyond "track changes".

Rather than storing a series of copies of a file with different filenames, Git captures a snapshot of your project each time you `commit`.
Try to think of your changes as separate from the document itself.
The file that you see in your folder is a specific set of edits that create that version, while the complete history of your project is safely stored in a hidden `.git` directory.

{% include figure.html file="versions.png" alt="file versions" caption="Adapted from: Software Carpentry, <a href='http://swcarpentry.github.io/git-novice/01-basics/' target='_blank'>Version Control with Git</a>" width="100%" %}

Each commit records the creator, email, and changes made, providing transparency and credit for your project, as well as, checksums to ensure no information can be lost or corrupted without detection.
Unlike "track changes", this history stays with the repository permanently.

Git is distributed meaning every copy of a repository contains the complete history. 
This is great for collaboration, fast performance, and offline usage.
Git can efficiently branch, diff, and automatically merge different sets of changes together, enabling people to work in parallel and sync their files.

{% include figure.html file="branch-merge.png" alt="branch and merge versions" caption="Adapted from: Software Carpentry, <a href='http://swcarpentry.github.io/git-novice/01-basics/' target='_blank'>Version Control with Git</a>" width="100%" %}

With Git you can make changes and experiment without fear!
Committing to a repository Git only adds data, it never deletes information. 
This makes almost everything undoable!

> A Git repository is often called a "repo"

## What is GitHub?

GitHub is a popular web service for hosting Git repositories--with benefits!
It provides a handy web interface for editing and collaborating on repos, as well as, built in project management features and static web hosting.
Accounts are free for public repositories--private repositories are available on a subscription pricing model.

GitHub is where the distributed part of Git gets really cool. 
With a central repo hosted on GitHub, you can easily collaborate with anyone in the world, or yourself across multiple computers, and never get out of sync with your project!

> There are other version control systems and cloud repository hosts, check the [Resources]({{ '/6-resources' | absolute_url }}) for more options.

## Plain Text Workflow

Git works best tracking [plain text](https://en.wikipedia.org/wiki/Plain_text) files.
All code (`.c`, `.py`, `.r`, `.html`, `.md`, etc) is plain text.
Most images, video, or [proprietary](https://www.gnu.org/proprietary/proprietary.en.html) document formats (such as Word's `.docx`) are not.
Git can tell exactly what changes in a plain text file, but can not understand the insides of a [binary file](https://en.wikipedia.org/wiki/Binary_file).
It will know when a binary file is changed, but it can not give you the exact differences.
Thus, Git is not optimal for managing Word docs, PDFs, or other binary files.
Instead, think about using a plain text writing workflow using [Markdown](https://evanwill.github.io/_drafts/notes/markdown-minute.html) or [LaTeX](https://www.latex-project.org/about/)--it simplifies your life, makes writing easier and more [sustainable](https://programminghistorian.org/lessons/sustainable-authorship-in-plain-text-using-pandoc-and-markdown)!

## Example Use

Software Carpentry, "Version Control with Git" lesson:

- An [example lesson](https://github.com/swcarpentry/lesson-example) and [web template](https://github.com/swcarpentry/styles/) are collaboratively maintained in GitHub repositories.
- Lesson content is created and edited in another [repository](https://github.com/swcarpentry/git-novice).
- Using the template style, the lesson repository generates a [web site](http://swcarpentry.github.io/git-novice/) hosted on Github.

Or check the [source code]({{ site.repo }}) of this site!
