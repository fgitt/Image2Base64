# Image 2 Base64

## Appearance / 外観

![Image2Base64.png](https://github.com/PhantomquartzPark/Image2Base64/image/Image2Base64.png)

## How To Use / 使い方
至ってシンプル．

* 上部の窪んでいるように見えるパネル内に画像をドラッグ・アンド・ドロップするだけで自動的にBase64文字列が生成される．その結果は下部のテキストボックスに出力される．
* 「コピーする」ボタンを押下することで，そのテキストをクリップボードにコピーする．
* 「リロードする」ボタンを押下することで，「接頭テキスト」「接尾テキスト」「データURL化の指定」を考慮し，文字列の再構成が行われる．
  * 「データURL化の指定」に対するチェックと，「接頭テキスト」の`!`指定は，Jupyter Notebookへの埋め込みの際に有効
  * 「接尾テキスト」の有効性は現状不明
