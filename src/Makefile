.PHONY: all clean

all: paper.pdf

paper.pdf: paper.tex
	LANG= latexmk $<

clean:
	latexmk -C
	rm -f *.bbl *.run.xml *.lol *.ist
