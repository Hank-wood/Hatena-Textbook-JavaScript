課題 4.1
================================================================

記事一覧を JavaScript によって動的に描画せよ

## 課題の目的

* JavaScript によるサーバーとの通信ができるようになる
 * サーバーサイドで JSON API を作成
 * JS から API を叩く

## 仕様

* 記事一覧の情報を JSON で返す API を作成する
  * レスポンスには記事の本文も含めること
  * 記事を全件一気に返さず、一定の記事数毎にページングするように
  * URI やパラメータ、 ページ毎の記事数などは自由
* 上で作成した API を JS から叩いて、記事一覧を表示するページを作成する
  * Ajax 用ライブラリ使用可
  * HTML 中には記事の情報を含んでないページを作って、JS で動的に記事を表示する
  * JS では最低限 (API が返す) 最初のページを表示するように
  * ページの URI は自由
