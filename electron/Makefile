latex:
	latex electron
ps:
	dvips electron.dvi -o electron.ps
clean:
	rm -f *.bak *.pstex* *.aux *.toc *.log *.out *.ps
dist:
	zip ../electron.zip electron.tex svepj.clo svjour.cls *.eps 
