# K suboru: proj4.tex
# Datum:    18.4.2024
# Autor:    Jaroslav Mervart (xmervaj00@stud.fit.vutbr.cz)
# Projekt:  ITY projekt 4

PROJ=proj4

$(PROJ).pdf: $(PROJ).tex
	latex $(PROJ).tex
	bibtex $(PROJ).aux
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf -sPAPERSIZE=a4 $(PROJ).ps

clean:
	rm -f $(PROJ).bbl $(PROJ).blg $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out 

clean-all: clean
	rm -f $(PROJ).pdf
