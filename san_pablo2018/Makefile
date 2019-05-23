LTX=SiPM_a_novel_photon_detector_becoming_a_classic

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

