---
layout: post
title: Using Markdown and Pandoc 
categories:
- Computers
tags: [markdown, pandoc]
status: publish
type: post
published: true
author: Dylan W. Schwilk

---
I put together a set of templates and a build system for writing scholarly
articles in markdown and building docx, pdf and html output. See https://github.com/schwilklab/pandoc-build-system

This allows you to use markdown and a bibtex database, but avoid using bibtex styles (styles are handled by pandoc-citeproc). The ideas and several templates were borrowed from  [Kieran Healy's](http://kieranhealy.org/) pandoc build system. See https://github.com/kjhealy/pandoc-templates and https://github.com/kjhealy/latex-custom-kjh

You will need on your machine: pandoc and pandoc-citeproc, latex (for pdf output).  Note to my students: You can try this out on pearse (in room 206D) easily as pearse has all the installed software you would need (pandoc, latex etc).

Also, just a reminder that my [student starter Emacs configuration][emacs-ss] works well. Just clone it into a brand new ~/.emacs.d folder. Again, easiest on linux, so try it out on pearse.

[emacs-ss]: https://github.com/schwilklab/emacs-starter
