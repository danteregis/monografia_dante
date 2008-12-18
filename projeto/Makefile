all:
	latex projeto
	bibtex projeto
	latex projeto
	pdflatex projeto
pdf:
	pdflatex projeto
	pdflatex projeto
	pdflatex projeto
	bibtex projeto
	pdflatex projeto
	evince projeto.pdf
clean:
	rm -f *.aux *.log *.blg *.bbl *.dvi *.ps *.pdf *.toc *.lot *.lof *.siglax *.symbolsx

