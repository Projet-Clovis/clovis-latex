# clovis-latex
A LaTeX package for creating Clovis study sheet-like documents.

![Example of what can be achieved with this package](img/example1.png)

It is based on the `mdframed` package.

# Example Gallery
![Danger & Definition](img/example1.png)

Source code :
```tex
\clovisDanger{
    You cannot divide by 0 ! This is \textbf{invalid} : $\frac{5x+3}{0}$ !!!
}

\clovisDefinition{Clovis LaTeX}{
    A \LaTeX-package for creating Clovis study sheet-like documents.
}
```

# Installation

For TinyTex you need theses libraries:
```bash
tlmgr install lastpage soul inconsolata fontawesome5 minted mdframed zref-abspage zref needspace etoolbox tikz ifthen pgf tikzpagenodes ifoddpage bookmark tcolorbox environ tikzfill pdfcol listings listingsutf8
```

And you must have Pygments installed:
```bash
sudo apt-get install python3-pygments
```
