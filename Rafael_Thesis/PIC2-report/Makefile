report.pdf:	report.tex refs.bib
			pdflatex report.tex;  pdflatex report.tex; bibtex report; pdflatex report.tex; pdflatex report.tex;

clean: 
			-rm report.pdf report.blg report.log report.out report.aux report.bbl

new:			clean report.pdf
