# K suboru: ITY_xmervaj00.tex
# Datum:    28.2.2024
# Autor:    Jaroslav Mervart (xmervaj00@stud.fit.vutbr.cz)
# Projekt:  ITY projekt 1

PROJ=ITY_xmervaj00

$(PROJ).pdf: $(PROJ).tex
	latex $(PROJ).tex
	latex $(PROJ).tex
	dvips -t a4 $(PROJ).dvi
	ps2pdf $(PROJ).ps

clean:
	rm -f $(PROJ).aux $(PROJ).dvi $(PROJ).log $(PROJ).ps $(PROJ).out

clean-all: clean
	rm -f $(PROJ).pdf
