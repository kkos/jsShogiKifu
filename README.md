jsShogiKifu
================

Masato Bitoさんによる[jsShogiKifu] (https://github.com/bto/jsShogiKifu)
と、knuさんによる改修(https://github.com/knu/jsShogiKifu)
のforkです。

独自機能を追加していきます。

最新のソースコードは[GitHub上](https://github.com/kkos/jsShogiKifu)にあります。


最近の変更
---------

* 棋譜ファイルの手動更新 (If-Modified-Since HTTPヘッダーによるチェックあり)
  Firefoxの場合、サーバ側で棋譜ファイルに対してPragma: no-cacheを指定して、
  キャッシュされないようにしなければ更新されない

* 表示される手順を通常の棋譜表記に

<!--
Local variables:
mode: markdown
coding: utf-8
end:
-->
