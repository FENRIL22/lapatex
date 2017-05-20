# lapatex
## What
markdownでtex系列の恩恵にあやかる．

## Now
pandoc -> tex変換 makefileだけ．

## Plan
ライブプレビュー(低負荷)とかを実装したい．

スライドにおける独自実装も行うかも．


## 参考(予定)
* 差分検知(特に生latex部分の検知)
	* git を叩く
	* [goemon+pandocを使う](http://qiita.com/sago35/items/20004723778d60aa95aa)
	* [ファイル更新監視ツールを作ってみた](http://qiita.com/secondarykey/items/6fa481cbdee24632e80e)
	* [Golangでファイルの更新を監視してみた](http://kwnktks0515.hatenablog.com/entry/2017/03/07/205142)
* コンパイルなど(表などのみコンパイルしてPDFとする)
	* [gnuplotのグラフをTikzに出力してLatex文書に貼り付ける](http://nomura.nagoya/?p=287)
* 埋め込み(LATEX的に表示．表などをコンパイルしてPDFを挿入する)
	* [PDFをHTMLに埋め込む方法](http://3media.biz/web/object-pdf-embed-in-html.html)


## Other
このソフトウェアは以下を利用しています．

* pandoc
* make
* (将来的に)go?

