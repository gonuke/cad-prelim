all: pdf

pdf: 
		pdflatex prelim && bibtex prelim && pdflatex prelim

preview: pdf
		evince prelim.pdf

clean:
		rm  *.out *.idx *.lof *.log *.toc *.aux *.bbl *.blg 
