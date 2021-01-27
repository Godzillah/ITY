NAME=proj3
PROJECT= xorsak02-fit.zip

all:
	latex $(NAME).tex
	latex $(NAME).tex
	dvips $(NAME).dvi -t -sPAPERSIZE=a4 
	ps2pdf $(NAME).ps 

clean:
	-rm -f $(NAME).aux $(NAME).ps $(NAME).dvi $(NAME).log $(NAME).pdf

zip:
	zip $(PROJECT) $(NAME).tex oniisan2.eps oniisan.eps Makefile etiopan.eps

unzip:
	unzip  $(PROJECT)