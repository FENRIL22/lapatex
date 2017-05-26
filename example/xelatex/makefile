all :
	@echo "This file cannot compile, sorry."

xelatex:
	pandoc main.md\
		-o output.pdf\
		--latex-engine=xelatex\
		-H h-xelatex.tex

debug:
	pandoc main.md\
		-o dg.tex\
		--latex-engine=xelatex\
		-H h-xelatex.tex
