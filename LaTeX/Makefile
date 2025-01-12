buildlatex=pdflatex -shell-escape

all:
	$(buildlatex) 03-Refactoring-und-technische-Schulden-in-agilen-Projekten.tex
	bibtex 03-Refactoring-und-technische-Schulden-in-agilen-Projekten
	$(buildlatex) 03-Refactoring-und-technische-Schulden-in-agilen-Projekten.tex
	$(buildlatex) 03-Refactoring-und-technische-Schulden-in-agilen-Projekten.tex
