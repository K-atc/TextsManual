PDFのExportで日本語対応させる
=============================

 

デフォルトのままPDFでエクスポートすると日本語が□で出てきてしまいます。出力時に適切なフォントが使われるようにしないといけません。

![](<img/notCJK.png>)

 

[本家でも書かれています][1]が、この問題を解決するためにCJK向けのtempleteを使用するようにします。本家からダウンロードしたものは以下のフォルダに置きます。

[1]: <http://www.texts.io/support/0007/>

-   Mac OSの場合、`~/Library/Application Support/Texts/`

-   Windowsの場合、`%LOCALAPPDATA%\Texts\`

ダウンロードしたtempleteはExportした時に選択できるようになります。

![](<img/templete.png>)

 

が、画像がページいっぱいに表示されないなど問題を抱えています（defaultでは書かれいているものがこちらに書かれていない(ﾟДﾟ)）。フォントは日本語、欧文を別々で指定できます。作者のCJK.xelatexを<a href="https://gist.github.com/K-atc/d9177b2a00ebe83fb41d#file-cjk-xelatex" target=_blank>gist</a>に上げてるのでこれを参考にしてください。

フォント名は英語表記の方がトラブルがないと思います。フォント管理ソフト(NexusFontなど)やAdobe製品で英語表記のフォント名を確認することができます。
