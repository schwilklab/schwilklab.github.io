Schwilk Lab webpage
===================

Author: Dylan W Schwilk

Built using [jekyll][jekyll] for [github pages]

Structure
---------

### Templates ###

There are four templates in _layouts:
- default.html: the basic template that includes the header and footer and then inserts the contents it is handed in a "page-background" div
- page.html: The template for regular pages (not posts): it uses default.html as its wrapper.  This template includes a page header and title, then a page content div, and withni that a single entry div representing the content it is handed
- post.html: very similar to page.html, but it omits the page title and instead inserts the post title as an "entry-title" div
- blog.html: The template for the blog page that lists post extracts

### Pages (in markdown) ###

The pages are all *.md files in the _pages directory.  Each defines its own permalink.

### Posts (in markdown) ###

The posts are in the _posts directory in typical jekyll markdown format.

[jekyll]: http://jekyllrb.com/
[gh-pages]: https://pages.github.com/
