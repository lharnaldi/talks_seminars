all: review_lcivale.pdf

review_lcivale.pdf: review_lcivale.tex library.bib mybooks.bib
	pdflatex review_lcivale.tex
	bibtex review_lcivale.aux
	pdflatex review_lcivale.tex
	pdflatex review_lcivale.tex
	#gnome-open review_lcivale.pdf
	xdg-open review_lcivale.pdf

clean:
	rm -rf *~ *.out *.spl *.aux *.dvi *.log *.bbl *.blg *.pdf
