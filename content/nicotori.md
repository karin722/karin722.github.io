---
title: NicoToriOSを生やしました
date: 2020-02-23 19:00:00
tags:
---
刈り取るかもしれない
<!-- more -->
<!-- toc -->
## これは何
DirtyUnicorn(以下DU)をベースにした高機能なカスタムROM。

## 特徴
独自の変更はそれほど多くありません。しかしこれから増やしていく"つもり"です。
- ホームボタンの修正(二重円のそれ)
- ロック画面の日付の()

DUの機能は以下の通りです。
- 電源メニューの編集
- ロック画面の時計のスタイル変更
- ステータスバーのネットワークトラフィックインジケーターの追加
- ステータスバーのクイックプルダウン
- ステータスバーに表示する項目の編集
- QSの縦横の項目数の編集
- 強力なテーマ機能
- その他諸々

さらにPixel3/xlでは
- Active Edgeの細かい感度の調整
- Active Edgeに割り当てるアクションの編集(長押しオプションもある)
が使用できます。

## ダウンロード方法
配布はまだしていません。ビルドしたい方は[manifest](https://github.com/NicoToriOS/android_manifest)があるので活用してください。device treeは[DU](https://github.com/DirtyUnicorns)にあるやつがそのまま使えます。

## 今後の課題
このROMはまだまだ未完成です。こうしたほうがいい、とかそういうのがあったら教えてくれると嬉しいです。PullRequestも募集中です。むしろください...。課題点は以下のとおりです。
- zipnameの編集
- ライセンスが怪しいフォントの削除
- 初期壁紙の差し替え
- bootanimation
- ビルドサーバー代
- NicoTori(DU) tweakの日本語訳

## ソースコード
- [Dirty Unicorn](https://github.com/DirtyUnicorns)
- [FlokoROM](https://github.com/FlokoROM)
- [NicoToriOS](https://github.com/NicoToriOS)