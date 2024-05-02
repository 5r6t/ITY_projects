# K suboru: ITY_xmervaj00.tex
# Datum:    22.3.2024
# Autor:    Jaroslav Mervart (xmervaj00@stud.fit.vutbr.cz)
# Projekt:  ITY projekt 2

PROJ=proj2

$(PROJ).pdf: $(PROJ).tex
	pdflatex $(PROJ).tex
	pdflatex $(PROJ).tex
	
clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out

clean-all: clean
	rm -f $(PROJ).pdf
