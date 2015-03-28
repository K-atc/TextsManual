Textsの概要
===========

Textsは、 [texts.io][1]
のMarkdownに特化した高機能テキストエディタ（有料）です。MacOS/Windows
両対応です。Markdownファイルの編集を行え、編集方法は
WYSIWYG（見た目と出力が同じ）寄りな感じです。なのでショートカットを多用しなければなりませんが、慣れればMarkdownを直でいじるよりもミスが少なくなります。

[1]: <http://www.texts.io/>

基本機能
--------

対応する機能を Welcome To Texts の編集画面で示します。

![](<img/WelcomeToTexts.jpg>)

TeXでよく使う機能はありそうなので、TeXで一から書くよりも、ここである程度書いておいてTeXに変換すると捗りそうですね（labelなどが無いのが辛いですが…）。少なくとも（演習の）レポートや進捗報告や日常的なメモには十分な破壊力を持ちます。

エクスポート
------------

サンプルとして
[sample.md][2]（例の数学公式集+α）を用意しました。これをエクスポートしてみます。

[2]: <sample.md>

[他の出力方法][3]はありますが、ここではPDFに絞って紹介します。

[3]: <http://www.texts.io/samples/>

PDF
---

変換後のファイルは [sample.pdf][4]
です。画像に変換したものを下に貼ります。templeteをうまく作ればなかなか綺麗なドキュメントを出力することができます。

[4]: <sample.pdf>

![](<img/sample.jpg>)

上のPDFを吐く時に使ったtemplete(Formal.xelatex)を<a href="https://gist.github.com/K-atc/d9177b2a00ebe83fb41d#file-formal-xelatex" target=_blank>gist</a>にあげておいたので参考にしてください。


地味に良いところ
----------------

Repeat Export があり、 `Ctrl+Shift+Alt+E
`で前回のエクスポートをやり直すことができます。
