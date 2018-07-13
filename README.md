# LIFFHelloWorld
LIFFアプリをFirebase上で動かすサンプル第一弾

# 目的
Firebase上でLineアプリを動かす。
内容は https://github.com/line/line-liff-starter にあるもの。
line-liff-starterからファイルを一部使用しています。

# 手順
https://qiita.com/gupuru/items/25a6722f6f802d3a5250 を参考にhostingする
Realtime Database は一旦いらないです。

public以下をendpointとしているのでpublic以下のファイルをおいてデプロイ
* index.html
* liff-starter.js
* style.css

https://qiita.com/kenakamu/items/44cba247ab51b6c5ed51 を参考にliffのcliを使ってFirebaseのhostを登録
返ってきたアプリURLをlineアプリで開くことで完了
