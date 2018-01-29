---
title: Home
---

# Introduction to version control with Git and GitHub

{% include figure.html file="xkcd_git_2x.png" alt="xkcd git" caption="<a href='https://xkcd.com/1597/' target='_blank'>xkcd git</a>" width="60%" %}

Do you have files like final.txt, final_revised.txt, final_revised2.txt, final_revised2_revised.txt? Version control WILL make your life better! 

[Git](https://git-scm.com/) is a [free](https://www.gnu.org/philosophy/free-sw.en.html) version control system originally developed for coordinating huge software development projects. 
However, Git is also great for personal uses such as organizing the code for your research project or the drafts and notes for writing an article. 
Pair Git with free hosting from [Github](https://github.com/) and you have a powerful platform for managing your code and writing while collaborating and sharing with others. 

This workshop will get you started with version control by introducing the basic Git workflow and commands, and will cover Github features for collaboration and sharing. 
Members of the university community from all disciplines are encouraged to attend as Github has diverse applications from managing code and technical documentation, to collaborative writing of lessons and articles, to setting up free blogs and websites. 
We will introduce Git on the command line and the Github web interface.

> hosted by [University of Idaho Library](http://www.lib.uidaho.edu/) {{ site.pub_year }}

<div class="toc" markdown="1">
## Contents:

{% for lesson in site.pages %}
{% if lesson.nav == true %}- [{{ lesson.title }}]({{ lesson.url | absolute_url }}){% endif %}
{% endfor %}
</div>

> built using [Jekyll](https://jekyllrb.com/) and [GitHub Pages](https://pages.github.com/)
>
> images and content: cc-by-sa <a href="https://github.com/{{ site.github_username }}">{{ site.author }}</a> {{ site.pub_year}}. (get [source code]({{ site.repo }}))
>
> <a href="http://creativecommons.org/licenses/by-sa/4.0/" rel="license"><img style="border-width: 0;" src="https://i.creativecommons.org/l/by-sa/4.0/88x31.png" alt="Creative Commons License" /></a>
