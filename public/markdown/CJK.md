PDFのExportで日本語対応させる
=============================

 

デフォルトのままPDFでエクスポートすると日本語が□で出てきてしまいます。

![](<img/notCJK.png>)

 

[本家でも書かれています][1]が、この問題を解決するためにCJK向けのtempleteを使用するようにします。本家からダウンロードしたものは以下のフォルダに置きます。

[1]: <http://www.texts.io/support/0007/>

-   Mac OSの場合、`~/Library/Application Support/Texts/`

-   Windowsの場合、`%LOCALAPPDATA%\Texts\`

ダウンロードしたtempleteはExportした時に選択できるようになります。

![](<img/templete.png>)

 

が、画像がページいっぱいに表示されないなど問題を抱えています（defaultでは書かれいているものがこちらに書かれていない(ﾟДﾟ)）。フォントは日本語、欧文を別々で指定できます。作者のCJK.xelatexを[gist][2]に上げてるのでこれを参考にしてください。

[2]: <https://gist.github.com/K-atc/d9177b2a00ebe83fb41d>
