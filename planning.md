# Publication plan

An architecture Body of knowledge will in the beginning contain

  * the NAF4 standard

and potentially it can also contain material such as

* Best Practices
* Training materials
* articles in a blog-like format (called posts in Jekyll)
   * comparison with other framework
   * strong and weak points in NAF4
   * How-to ?
   * The tool landscape - a comparison of different tools (a minefield, which should be treated carefully)
* description of the NAF4 exchange format
* a test suite for the exchange format
* Proposals for new features in NAF4
* data on the standard (Keith's material) an potential other material, which can be processed and presented in various ways including graphical.
* a reference of open source NAF tools available, for presentation, analyzing, etc.
* NAF4 for dummies, grandmothers, generals etc.
* ...

##  Information  architecture

How should information be organized?

* NAF in chapters
* NAF + other stuff
* A reorganized NAF. The web is not a book and are not friendly to huge amount of text.


In a book the conclusion is the last chapter. On the web it is the first or at
least a condensed version is. Next step: is the condensed version sufficient?

We need policy for improvement. A book is final until the next version - the web
is always changing - we should be able to propose changes to at least the text
(not the meta model and viewpoints) between version - even when we are retired.

Final Goal: your grandmother should understand all of it.

A first version on the web will properly be a verbatim version of the docs, but
it would be prudent if the web version focus on the most important stuff, and
then link to pages with a more detailed material or pages with material, which
are less significant. This will require a complete reorganization of the
material.




## Converting word documents

A first step to creating an architecture body of knowledge including
documentation for NAF 4, will be to transform existing documentation in Word to
markdown of HTML. This work can be split into a small number of work packages,
where several of the work packages can be implemented more or less independently
of each other.

* Transforming the existing documents from Word to Github flavored markdown - can be done with Pandoc.
   * Organization of pages
* Deciding of a palette for images
* Recreating the images - preferable using SVG
* Defining layout templates for the site and different document types
   * default.html - Basic HTML header/body structure used by all pages.
   * spec.html - used by the NAF4 specification (needs a layout with
      navigation, which mimics a book).
   * ???
* Creating CSS styles (potentially a style guide)
* Defining reusable components
   * ...
* How to handle binary files such as images, PDF files etc. - a solution could be to use Git LFS
* Social Media: Twitter (properly not), Github, YouTube.
* Google analytics, SEO

## Outstanding issues

* Nafdocs? GitHub organization, nafdocs.org Ownership
* What to do with the material on the existing site
* Github flavored markdown

# Governance

Governance and usage of GitHub facilities - should properly be split up in two or more sections.

* Usage of issues (proposals and comments) and pull requests (provide changes to the repository)
* Milestones
* Decision
* Delegation of responsibility
* Who - Arch CaT
* Mapping of governance roles to GitHub organizational roles.

# References

* Markdown - https://daringfireball.net/projects/markdown/
* Jekyll Screencasts (34 videos) -  https://youtu.be/oiNVQ9Zjy4o?list=PLWjCJDeWfDdfVEcLGAfdJn_HXyM4Y7_k-
* Git Large File Storage (LFS) - https://git-lfs.github.com/
* Jekyll documentation - http://www.jekyllrb.com
* GitHub Guides - https://guides.github.com/
* Github Help - https://help.github.com/
* Github Organisational Accounts -https://help.github.com/categories/setting-up-and-managing-organizations-and-teams/
