# Autoreg CSF Presentation CyberGIS14

This is a Beamer presentation being build with Freemind and xsl exports.

## Dependencies

1. [Freeplane]
2. [freemind2beamer]


### Setup

1. `git clone https://github.com/igor-go/mm_xslt_exports.git` or grab file [mm2latexbeamer_richcontent.xsl] from the online repos
2. Place the  `mm2latexbeamer_richcontent.xsl` file in  `~/.freeplane/xslt/`
3. Open up the autocsf.mm file in freeplane
4. `File-Export` then under `filter` select `Latex Beamer (.tex)`.
5. Open the file `autocsf.tex` in a LaTeX editor or run `pdflatex autoregcsf` several times
6. Open up autocsf.pdf in a viewer.
7. Modify the autocsf.mm to add slides
8. Repeat 4-7 until done.


Note that this might work with freemind as well, but I've not used freemind in a couple of years.

[Freeplane]:  http://sourceforge.net/projects/freeplane/
[freemind2beamer]: https://sites.google.com/site/freemind2beamer/
[mm2latexbeamer_richcontent.xsl]:https://raw.githubusercontent.com/igor-go/mm_xslt_exports/master/mm2latexbeamer_richcontent.xsl 
