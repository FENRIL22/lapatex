.SUFFIXES: .tex .dvi .pdf .bib .bbl
FONT = res/font/ipaex.map
InputauxFiles = $(wildcard c_*.aux)
InputTeXFiles = $(wildcard c_*.tex)

all :
	make main.pdf

main.pdf :
	pandoc main.md -o tmp-1.tex
	cat tmp-1.tex | grep -v "tightlist" | cat > tmp.tex
	platex -interaction=batchmode -draftmode format
	platex -interaction=batchmode format.tex
	dvipdfmx -f res/font/ipaex.map -I 12 format.dvi

debug :
	pandoc main.md -o tmp-1.tex
	cat tmp-1.tex | grep -v "tightlist" | cat > tmp.tex
	platex format
	platex format.tex
	dvipdfmx -f res/font/ipaex.map -I 12 format.dvi

clean:
	rm -rf *.aux *.dvi *.log *.bbl *.blg *.out *.toc *.pdf tmp*.tex

# Data
# MarkdownとPandocを用いた簡易Latex環境の構築
# http://qiita.com/mountcedar/items/e7603c2eb65661369c3b
# markdown->TeXの変換だけで卒論を仕上げるのに便利だったツール10個まとめ# http://mizchi.hatenablog.com/entry/2014/01/20/090957
