<link href="http://kevinburke.bitbucket.org/markdowncss/markdown.css" rel="stylesheet"></link>
<link href="markdown_modified.css" rel="stylesheet"></link>

## Tools for Reproducible Research

### Draft outline, Spring 2014


#### Jan 24: Basic principles
 - replicable vs reproducible
 - need "pipeline": data & code available and use documented
 - "best practices" more generally...
 - finding answers to questions:
   - help files / manual pages
   - google
   - [stackoverflow](http://stackoverflow.com)
   - email lists / google groups
   - friends / colleagues
 - Automation with make

---

#### Jan 31: Know the command line; know your editor

Point-and-click is _not_ reproducible.

Editors:
 - emacs with ESS
 - vim
 - Rstudio
 - textwrangler
 - notepad++
 - Tinn-R

Use relative paths rather than absolute paths, and don't jump out of
the current directory.

---

#### Feb 7:  Knitr with markdown/asciidoc for basic reports

- including figures and tables
  ([xtable](http://cran.r-project.org/web/packages/xtable/index.html)
  to html or asciidoc tables with the
  [ascii package](https://github.com/eusebe/ascii/)


---

#### Feb 14: Big jobs/simulations; caching computations

---

#### Feb 21: Version control with git & github/bitbucket

 - Also, facilities through Rstudio

---

#### Feb 28: Capturing exploratory analysis

---

#### Mar 7: Writing R packages; Roxygen2

 - Assemble related code into a package, with help files
 - Write a package for your own miscellaneous tools
 - [Jeff Leek on developing R packages](https://github.com/jtleek/rpackages)

---

#### Mar 14:  Writing clear code

 - Break things up into small functions
 - Don't repeat yourself
 - Use meaningful names
 - Don't be cute

Example: [tweet re function names](https://twitter.com/richierocks/status/388609208293556224)

---

#### Mar 28: Software testing and debugging

 - testthat package
 - [Hadley Wickham's paper](http://journal.r-project.org/archive/2011-1/RJournal_2011-1_Wickham.pdf)

---

#### Apr 4: Organizing data analysis projects

---

#### Apr 11:  Knitr with latex for papers

- including figures and tables

---

#### Apr 18: Presentations

---

#### Apr 25: Posters

---

#### May 2:  Ruby/python/perl for data/text manipulation

---

#### May 9:  Software/data licenses, copyright, and human subjects/HIPPA

 - good overall ref?
 - GPL, MIT, BSD, WTFPL
 - [coding horror blog](http://www.codinghorror.com/blog/2007/04/pick-a-license-any-license.html)
 - HIPPA / human subjects


---

#### Other resources

- [roger peng slides](http://www.stodden.net/AMP2011/slides/pengslides.pdf)
- [yihui slides](http://yihui.name/slides/2012-knitr-RStudio.html)