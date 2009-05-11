latex:
	latex electron
ps:
	dvips electron.dvi -o electron.ps
pdf:
	pdflatex -shell-escape electron # -shell-escape is required by epstopdf
clean:
	rm -f *.dvi *.pdf *.bak *.pstex* *.aux *.toc *.log *.out *.ps
dist:
	zip ../electron.zip electron.tex svepj.clo svjour.cls *.eps 
