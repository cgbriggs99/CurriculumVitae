.PHONY:all
all: cv.tex cv.bib
	pdflatex cv.tex
	bibtex cv.aux
	@pdflatex cv.tex 1&>/dev/null
	@pdflatex cv.tex 1&>/dev/null

.PHONY:clean
clean:
	rm -rf cv.aux cv.bbl cv.bib~ cv.blg cv.log cv.out cv.tex~
