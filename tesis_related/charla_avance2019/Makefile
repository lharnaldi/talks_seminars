LTX=charla_avance

all: $(LTX).pdf

$(LTX).pdf: $(LTX).tex 
	#pdflatex $(LTX).tex
	#bibtex $(LTX)
	#bibtex $(LTX)
	pdflatex $<
	pdflatex $<
	#gnome-open $(LTX).pdf
	xdg-open $@

clean:
	rm -rf *~ *.toc *.snm *.nav *.out *.aux *.dvi *.log *.bbl *.blg $(LTX).pdf

