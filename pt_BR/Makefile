all: cv.pdf

cv.pdf: cv.tex
		pdflatex cv.tex
		pdflatex cv.tex

clean:
		rm -rf *.aux *.dvi *.log *.out

cleanall: clean
		rm -rf *.pdf
