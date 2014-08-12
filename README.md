# Autoreg CSF Presentation CyberGIS14

This is a Beamer presentation being build with Freemind and xsl exports.

## Dependencies

1. [Freeplane] (this example is using 1.3.11 on Mac OS X)
2. [freemind2beamer]


### Setup

1. `mkdir ~/.freeplane/1.3.x/xslt` 
2. `cd ~/.freeplane/1.3.x/xslt`
1. `curl -O https://raw.githubusercontent.com/igor-go/mm_xslt_exports/master/mm2latexbeamer_richcontent.xsl`
3. In our project repos, open up the `autocsf.mm` file in freeplane
4. `File-Export` then under `filter` select `Latex Beamer (.tex)`.
5. Open the file `autocsf.tex` in a LaTeX editor or run `pdflatex autoregcsf` several times
6. Open up autocsf.pdf in a viewer.
7. Modify the autocsf.mm file to add/or modify slides
8. Repeat 4-7 until done.


Note that this might work with freemind as well, but I switched from freemind to freeplane a few years back.

[Freeplane]:  http://sourceforge.net/projects/freeplane/
[freemind2beamer]: https://sites.google.com/site/freemind2beamer/
[mm2latexbeamer_richcontent.xsl]:https://raw.githubusercontent.com/igor-go/mm_xslt_exports/master/mm2latexbeamer_richcontent.xsl 
