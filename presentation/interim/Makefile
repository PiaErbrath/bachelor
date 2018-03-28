all: main clean

main:
	pdflatex presentation.tex
	makeglossaries presentation
	pdflatex presentation.tex
	pdflatex presentation.tex

clean:
	rm -f *.log *.lof *.lot *.toc *~ *.aux *.fls *.out *.bbl *.blg *.hst *.ver *.lol *.synctex.gz *.bcf *.run.xml *-blx.bib *.acn *.acr *.alg *.glg *.glo *.gls *.glsdef *.ist *.xdy *.glsdefs

cleanall: clean
	rm -f presentation.pdf
