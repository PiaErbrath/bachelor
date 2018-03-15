all: main clean

main:
	pdflatex main.tex
	makeglossaries main
	biber main
	pdflatex main.tex
	pdflatex main.tex
	cp main.pdf thesis.pdf

clean:
	rm -f *.log *.lof *.lot *.toc *~ *.aux *.fls *.out *.bbl *.blg *.hst *.ver *.lol *.synctex.gz *.bcf *.run.xml *-blx.bib *.acn *.acr *.alg *.glg *.glo *.gls *.glsdef *.ist *.xdy *.glsdefs
	

cleanall: clean
	rm -f main.pdf thesis.pdf

otherclean:
	rm -f *.log *.lof *.lot *.toc *~ *.aux *.fls *.out *.bbl *.blg *.synctex.gz *.maf *.mtc *.mtc0 *.snm *.nav *.glo *.glsdefs *.ist *.vrb *.bcf *.run.xml
