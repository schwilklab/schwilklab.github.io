---
layout: post
title: Plain text workflows for graduate students
categories:
- Computers
tags: [markdown, pandoc]
status: publish
type: post
published: true
author: Dylan W. Schwilk

---
Markus Eichhorn just wrote a [nice post describing writing tools for biologists](http://treesinspace.com/2016/02/16/open-source-software-for-biologists-pt-1-writing-tools/)
That prompted me to put down a few thoughts quickly both to describe the tools I use but also suggest a possible path for the student interested in moving away from a ms word only workflow but for whom my emacs-only setup is too foreign.

I'm a big proponent of a plain-text workflow for two main reasons: 1) version control for everything and 2) I become competent at one editor I use for everything.

But I have given thought to how how to help my students who want to move to better writing and coding workflows. The main obstacle for them is that my own setup (emacs for everything) seems very foreign to them and there is an activation energy hurdle in the way. The path of least resistance that seems to work for them has been:

1. First the student sees the value of version control for code (they use R and RStudio). Git has a difficult learning curve, but I've just had to make basic git required in my lab.
2. This leads to a desire to use version control for other things such as lectures, lab notes, and manuscripts.
3. The student tries out plain text for writing other than R code. For example, she uses rmarkdown in RStudio.

From here the student may decide to go the emacs route or another way. Or decide to work with text for code but use Microsoft or LibreOffice for prose. My students use Mendeley to manage citations.

My own setup? I use emacs with packages like org-mode, magit, and ess. With one editor I

- keep all my scheduling/notes/todo lists in plain text with [org-mode](http://orgmode.org/),
- write lectures for multiple output formats (org-mode with output to slides pdf for classroom lecture, output to html for course website or pdf for notes, etc).
- use version control with emacs [magit](https://github.com/magit/magit) as a nice front end,
- write and run R ([ess](http://ess.r-project.org/)) and python code, 
- write manuscripts (org mode, markdown or sometimes LaTeX). But for manuscript collaboration I often find myself using LibreOffice (MS Word format) with others. That's fine. One nice thing about using markdown with pandoc is it is pretty easy to compile to MS Word if the journal requires that. But tables are limited in markdown.

For the curious, my [emacs configuration is on github](https://github.com/dschwilk/emacs-config) and the build system I've used for markdown and [pandoc](http://pandoc.org/) is based on [Kieran Healy's](http://kieranhealy.org/).
