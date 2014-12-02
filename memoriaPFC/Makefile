all: memoPFC.pdf

memoPFC.pdf: memoPFC.tex
	pdflatex memoPFC.tex; bibtex memoPFC; pdflatex memoPFC.tex

clean:
	rm -f memoPFC.dvi memoPFC.ps *.snm *.out *.nav *.log *.aux *.toc *.vrb *.pdf *~
