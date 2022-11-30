# mashi_site.github.io

これはマークダウンでレポートを書くときに読み込む CSS ファイルを作成してみたのでネット上にあげてみようと思って作ったサイトです。

内容はないので CSS ファイルの冒頭のコメント（↓のコードです）をマークダウンの先頭に書いて [VS Code の拡張機能のPDF化するやつ](https://marketplace.visualstudio.com/items?itemName=yzane.markdown-pdf)でpdf化させてください。

```
<link href="https://raw.githubusercontent.com/KaoruHOSOKAWA/test-site/main/latex.css" rel="stylesheet">
<script type="text/javascript" async src="https://cdnjs.cloudflare.com/ajax/libs/mathjax/2.7.7/MathJax.js?config=TeX-MML-AM_CHTML"></script>
<script type="text/x-mathjax-config">
 MathJax.Hub.Config(
  {
    tex2jax: {
     inlineMath: [['$', '$'] ],
     displayMath: [ ['$$','$$']]
    }
  }
 );
</script>
```
