To use, put the following text into a Makefile:

   include pages-builder/included_make

The scripts expect there to be a directory called talks. Each subdirectory is a separate "talk". 

In each talk subdirectory, all .tex files are turned into a .pdf. In addition a notes.tex file is converted into html. Slides in beamer format therefore become a .pdf.