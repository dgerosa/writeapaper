compile:
	rm -rf *aux *blg *bbl *synctex* *Notes.bib *log *out
	pdflatex draft
	bibtex bu1.aux 
	bibtex bu2.aux
	pdflatex draft
	pdflatex draft
