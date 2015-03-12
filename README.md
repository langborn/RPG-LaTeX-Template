# D&D 5e LaTeX Template

This is a prelimary attempt at a D&D 5e LaTeX template. The color scheme is close to the original source books, as are the fonts. The fonts chosen are included by default in TeX Live.

An example of a table with alternating row colors is given. It's a bit gross, however, and a lot could be done to clean that up.

The template compiles with pdflatex.

![Preview](https://github.com/evanbergeron/DND-5e-LaTeX-Template/raw/master/scrot.png)


### Installation

Just clone the repo. From terminal:

```sh
$ git clone [git-repo-url] 5e-template
$ cd 5e-template
$ pdflatex main.tex
```

### Todo's

 - Wrap tables up in macros
 - Export most of the preamble to a .cls file
 - Consider implementing more complex tables for monsters, etc.

### Version
0.1
