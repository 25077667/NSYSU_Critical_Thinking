all: eng chn

eng:
	pdflatex  -synctex=1 -interaction=nonstopmode -shell-escape -enable-write18 -recorder ct.tex
chn:
	xelatex ct-CHN
	biber ct-CHN
	xelatex ct-CHN
	xelatex ct-CHN

