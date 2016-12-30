SuperLimitBreak band rider repository
=====================================

How to generate PDFs
--------------------
Pandoc can be used to generate PDFs cleanly from markdown (with embedded LaTeX)

```bash
pandoc -o nameOfOutputFile.pdf nameOfInputFile.md
```

Dependencies
------------

- [pandoc](http://pandoc.org/). This is available pre-built in most operating
  system's repositories.
- [LaTeX](http://www.tug.org/texlive/), TeX Live specifically. Again available
  pre-built in most operating system's repositories.

### Examples

On Debian (Ubuntu etc.):
```bash
sudo apt-get update
sudo apt-get install texlive
sudo apt-get install pandoc
```

