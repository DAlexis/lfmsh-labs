all: list-with-hints.pdf list-no-hints.pdf

%.pdf: %.tex
	pdflatex --shell-escape -synctex=1 -interaction=nonstopmode $<
