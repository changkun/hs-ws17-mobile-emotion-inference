all:
	latexmk -pdf lmumihs.tex
	mv lmumihs.pdf lmumihs-ou.pdf
	make clean
	open lmumihs-ou.pdf
clean:
	rm -f *.fdb_latexmk *.fls *.dvi *.aux *.log *.toc *.glo *.idx *.ilg *.out *.bbl *.thm *.blg *.lot *.lof *.xdv *.xml *-blx.bib