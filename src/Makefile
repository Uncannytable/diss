SRCTEX=$(wildcard *.tex)

MAIN=main

all: $(MAIN).pdf

$(MAIN).pdf: $(SRCTEX) bibfile.bib
	latexmk -pdf $(MAIN)
	evince $(MAIN).pdf &



clean:
	rm -f *.o *.aux *.log *.out *.bbl *.toc *.pdf *.blg *.dvi *~ *.fls *_latexmk *.spl
