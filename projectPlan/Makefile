all: main clean

main:
	pdflatex main.tex
	makeglossaries main
	pdflatex main.tex
	pdflatex main.tex
	mv main.pdf projectplan.pdf

clean:
	rm -f *.log *.lof *.lot *.toc *~ *.aux *.fls *.out *.bbl *.blg *.hst *.ver *.lol *.synctex.gz *.bcf *.run.xml *-blx.bib *.acn *.acr *.alg *.glg *.glo *.gls *.glsdef *.ist *.xdy *.glsdefs

cleanall: clean
	rm -f main.pdf projectplan.pdf
