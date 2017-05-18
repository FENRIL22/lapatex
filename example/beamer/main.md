% Title
% User Name
% 20xx/4/1


# First Page
## 1つのブロック
普通の節のようにするとbeamerではブロックになったり．

これはそのデザインに依存する．

## 2つのブロック
* このように
* リストも入る


# カラーボックスなど
基本beamerなので直接beamer(tex)記法が使える

<!-- colorset -->
\setbeamercolor{white-cyan2}
{fg=black,bg=red!20!white}

<!-- colorbox -->
\begin{beamercolorbox}[ rounded=true, shadow=true]{white-cyan2} 
ColorBox
\end{beamercolorbox}

<!-- block -->
\begin{block}{内容の通知}
block
\end{block}

\begin{alertblock}{内容の通知}
alertblock
\end{alertblock}

\begin{exampleblock}{内容の通知}
exampleblock
\end{exampleblock}


# Picture
<!-- その他(画像のはりつけ) -->
\centering

<!-- Pictureのキャプションを消すには\ を使い，中央寄せと左寄せに戻すためにコマンドを用いる -->
![](url.png)\

\raggedright

<!-- url などを小さく出す時は\tinyなどを使う -->
[\tiny hogefuga](hoge)


# 注意
スライド中にわずかでも通常の分(ここみたいなもの)が無いと，正常に生成されないので注意.
