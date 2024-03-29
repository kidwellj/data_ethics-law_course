This repository contains the contents of a short open course designed by Jeremy H. Kidwell and Alex Fenlon at the University of Birmingham. The module explores ethical and legal issues surrounding contemporary academic research and engagement with (especially digital) data. 

The course here has been compiled with [bookdown](https://github.com/rstudio/bookdown), and so the live instance of the course is compiled from openly accessible resources located in this repository. If you're interested in doing something similar, there are a number of good options, including: [gitbook](https://docs.gitbook.com/), [mkdocs](https://www.mkdocs.org/), [readthedocs](https://readthedocs.org) which technically uses [Sphinx](http://www.sphinx-doc.org/en/master/) or [daux](https://daux.io/).

Directory structure includes:
* `README.md` this README file displayed on Github
* `docs` a folder containing the compiled book in html, .pdf and epub formats
* `course.bib` a bibliography of items used for the course in [BibTeX format](http://www.bibtex.org/Format/)
* `index.Rmd` Contains initialization settings, and preface content
* `01-Overview.Rmd` Introduction and overview to course
* `02-Session1.Rmd` First chapter: "what is data?"
* `03-Session2.Rmd` Second chapter: "copyright, licenses, and data as property"
* `04-Session3.Rmd` Third chapter "exploring confidentiality and privacy"
* `05-Session4.Rmd` Fourth and closing chapter: "how do we decide what to do?"

There are videos which accompany the curriculum, which can be [found on PeerTube](https://peertube.co.uk/my-library/video-playlists/35b0f942-b944-42aa-aa7b-6e129b403271). 

Content here, unless otherwise indicated are copyright by Jeremy H. Kidwell and Alex Fenlon. But please re-use them as they are covered by [Creative Commons Attribution 4.0 International Licence (CC BY 4.0)](http://creativecommons.org/licenses/by/4.0).

# How to produce 'books' from this repository using bookdown

1. Clone this repository so you have a local directory to work with
2. You can use `make` from the command line, which calls the `Makefile` provided here OR
3. Working in R Studio, load the `bookdown` library, and then from within the root directory of this repo, invoke the command `bookdown::render_book("index.Rmd", "bookdown::gitbook")`
