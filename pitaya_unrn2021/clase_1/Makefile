LTX=clase_1

all: $(LTX).pdf

$(LTX).pdf: $(LTX).tex 
	#pdflatex $(LTX).tex
	#bibtex $(LTX)
	#bibtex $(LTX)
	pdflatex $(LTX).tex
	pdflatex $(LTX).tex
	#gnome-open $(LTX).pdf
	xdg-open $(LTX).pdf

clean:
	rm -rf *~ *.toc *.snm *.nav *.out *.aux *.dvi *.log *.bbl *.blg $(LTX).pdf

