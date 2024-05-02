# K suboru: proj5.tex
# Datum:    2.5.2024
# Autor:    Jaroslav Mervart (xmervaj00@stud.fit.vutbr.cz)
# Projekt:  ITY projekt 5

PROJ=proj5

$(PROJ).pdf: $(PROJ).tex
	pdflatex $(PROJ).tex
	pdflatex $(PROJ).tex

clean:
	rm -f $(PROJ).dvi $(PROJ).aux $(PROJ).log $(PROJ).nav $(PROJ).toc $(PROJ).snm $(PROJ).out $(PROJ).vrb

clean-all: clean
	rm -f $(PROJ).pdf
