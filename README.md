Schwilk Lab webpage
===================

Author: Dylan W Schwilk

Built using [jekyll][jekyll] for [github pages][gh-pages]

Overview
--------

### Templates ###

There are four templates in _layouts:
- default.html: the basic template that includes the header and footer and then inserts the contents it is handed in a "page-background" div
- page.html: The template for regular pages (not posts): it uses default.html as its wrapper.  This template includes a page header and title, then a page content div, and within that a single entry div representing the content it is handed
- post.html: very similar to page.html, but it omits the page title and instead inserts the post title as an "entry-title" div
- blog.html: The template for the blog page that lists post extracts

### Pages (in markdown) ###

The pages are all *.md files in the _pages directory.  Each defines its own permalink.

### Posts (in markdown) ###

The posts are in the _posts directory in typical jekyll markdown format.


Directory structure
-------------------

.
|-- css
|-- downloads
|-- images
|-- _includes
|-- _layouts
|-- _pages
|-- _posts


### css ###

css styles

### downloads ###

Static content that is not an image or html

### images ###

Store all images here

### _includes ###

Header and footer definitions using liquid

### _layouts ###

Liquid tempaltes described above

### _pages ###

Web pages in Markdown

### _posts ###

weblog posts


Building
--------

To update the site, simply push changes and github will rebuild using jekyll.  To preview the site locally before pushing changes, you need to run jekyll serve and point your browser to localhost:4000


### Requirements ###

- jekyll
- jekyll-redirect-from


[jekyll]: http://jekyllrb.com/
[gh-pages]: https://pages.github.com/
