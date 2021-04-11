# bookofgeometron

![](cover.png)

## A new version of a unified manuscript documenting the Geometron system, intended for wider distribution

## Chapter Outline

 - Civilizations
 - Organic Media
 - The Street Network
 - Code
 - Scrolls
 - Maps
 - Feeds
 - Symbols
 - 2d Web Graphics
 - Shapes and fonts
 - Machine Control
 - Geometron in 3d and beyond
 - Ontology
 - Trash Robot
 - Full Stack Geometron

Manuscript is written in LaTeX.  Markdown documents from Geometron are stored in scrolls/ directory, then converted from .md to .tex using pandoc at the *nix command line: pandoc -o filename.tex filename.md.  Files in .tex format are then copied to main directory and edited there using Visual Studio Code.  Main.tex is the main LaTeX document which incorporates each of the chapters into a book format document, saved at main.pdf.  This is the main working copy of the full manuscript.  Opening it in Github can be unwieldy and cause github to crash your browser however. 