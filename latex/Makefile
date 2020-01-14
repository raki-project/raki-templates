default: pdflatex clean

pdflatex:
	pdflatex main.tex
	bibtex main
	pdflatex main.tex
	pdflatex main.tex

clean:
	rm *.aux *.bbl *.blg *.out *.log *.toc
