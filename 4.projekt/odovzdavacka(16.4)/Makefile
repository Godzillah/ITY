all:
	latex proj4
	bibtex proj4
	latex proj4
	latex proj4
	dvips proj4.dvi -t -sPAPERSIZE=A4
	ps2pdf proj4.ps

clean:
	rm -r proj4.ps proj4.pdf proj4.log proj4.dvi proj4.blg proj4.bbl proj4.aux

zip:
	zip xorsak02-fit.zip Makefile proj4.tex reference.bib czplain.bst

unzip:
	unzip xorsak02-fit.zip