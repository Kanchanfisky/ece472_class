FILE=ECE472_HW5_branaugj_kuceyb

default:
	pdflatex $(FILE).tex
	make clean

clean:
	rm $(FILE).aux
	rm $(FILE).log
	rm $(FILE).out

display: default
	evince $(FILE).pdf &
