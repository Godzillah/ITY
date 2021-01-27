NAME=proj5

all:
	pdflatex $(NAME).tex

clean:
	rm -f $(NAME).aux $(NAME).log $(NAME).dvi $(NAME).ps $(NAME).out $(NAME).toc $(NAME).snm $(NAME).nav $(NAME).pdf 


zip:	
	zip xorsak02-fit.zip $(NAME).tex Makefile DKA_vs_NKA.png nedeterministicky-konecny-automat-5fb817ed126c31736b4a776ce42cc7cc.png NKA_DKA.png

unzip:
	unzip xorsak02-fit