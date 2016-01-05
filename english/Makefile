ARCHIVO = main

main:
	pdflatex $(ARCHIVO).tex
	# bibtex pulications.bib
	pdflatex $(ARCHIVO).tex

clean:
	rm *.txt *.log *.aux *.make *.bak *.d *.fls *.toc *.out
	rm -rf *~
