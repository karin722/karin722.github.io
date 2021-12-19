+++
title= "ubuntuにおけるios14のfuturerestoreについて"
date = 2021-02-20 18:55:44
[taxonomies]
tags = ["Jailbreak"]
[extra]
author = "karin722"
+++
備忘録
<!-- more -->
## 環境
- vmware workstation 16
- ubuntu 20.04lts
- bash

iphone6s 14.4 -> 14.3rc で動作確認しました

## vmware側の設定
仮想マシン設定 > USBコントローラ > USBの互換性 を3.1に設定してください。そうしないとFuturerestoreが通常状態のiPhoneを認識できないようです
![frusb](/FR_su.png)

## ビルドする
ubuntu20.04ltsなら[これ](https://raw.githubusercontent.com/LukeZGD/LukeZGD.github.io/master/scripts/futurerestore_compile.sh)を実行すれば勝手にビルドしてくれます。すごいね

途中で「Enter Y if futurerestore will be used on A13/A14 devices」とか言われるので、実行したい端末と相談してYとかNとか押してください。PCの前でシャゲダンをするとビルド時間が縮まるようです

## 実行
[tools4hack](https://tools4hack.santalab.me/howto-tutorial-futurerestore-restore-update-downgrade-to-ios1131.html)みて頑張ってください。2年前の記事ですが、使用方法は変わっていません

> a12/a13/a14は実行前にapnonceの確認を忘れずに！切り替わっている可能性もあります

![fr](/FR_su.png)
<br>チンパンジーは成功させましたよ、ニンゲン共は？