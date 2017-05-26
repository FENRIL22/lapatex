all :
	#@echo "This file cannot compile, sorry."
	make xelatex

xelatex:
	pandoc main.md\
		-o output.pdf\
		--latex-engine=xelatex\
		-N\
		-V geometry:margin=1in\
		--toc\
		-V documentclass:bxjsarticle\
		-V classoption:xelatex\
		-V classoption:ja=standard\
		-V classoption:jafont=hiragino-pron\
		-H h-xelatex.tex
		#--filter pandoc-crossref\
		#--bibliography references.bib\

debug:
	pandoc main.md\
		-o dg.tex\
		--latex-engine=xelatex\
		-H h-xelatex.tex
