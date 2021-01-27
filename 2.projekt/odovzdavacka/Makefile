name=proj2

all:
	latex $(name).tex
	latex $(name).tex
	dvips -t a4 $(name).dvi
	ps2pdf $(name).ps

clean:
	rm -r proj2.aux
	rm -r proj2.dvi
	rm -r proj2.log
	rm -r proj2.pdf
	rm -r proj2.ps

zip:
	zip xorsak02-fit.zip Makefile proj2.tex 