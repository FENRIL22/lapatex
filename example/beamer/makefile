all :
	make beamer

beamer:
	pandoc main.md\
		-o output.pdf\
		--latex-engine=lualatex\
		-t beamer\
		-V theme:Madrid\
		-V colortheme:beaver\
		-H h-lualatex.tex

bk:
	pandoc main.md\
		-o output.pdf\
		--latex-engine=lualatex\
		-t beamer\
		-V theme:CambridgeUS\
		-V colortheme:dove\
		-V fontsize:20pt\
		-H h-lualatex.tex
