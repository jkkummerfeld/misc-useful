name=example
tex=pdflatex
bib=biber

all: paper

paper: *.tex *.bib
	${tex} cover-letter
	$(tex) ${name}
	${bib} ${name}
	$(tex) ${name}
	$(tex) ${name}

tex: *.tex
	$(tex) ${name}

clean:
	rm ${name}.aux ${name}.bbl ${name}.bcf ${name}.blg ${name}.log ${name}.run.xml ${name}.toc ${name}.out

