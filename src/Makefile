TEX = latexmk -pdflatex='pdflatex -file-line-error -synctex=1' -pdf

.PHONY: all view

all : example.pdf

example.pdf : example.tex
	$(TEX) example.tex
	
make clean:
	rm *.pdf *.aux *.log *.nav *.out *.snm *.synctex.gz *.toc *.fdb_latexmk
