# この説明書はGP2040-CEの補足資料
この説明書は、かぬコンで追加した機能に関する部分のみ説明します。
詳しい使い方は、[GP2040-CE](https://gp2040-ce.info/#/)　をご確認ください。
# Webconfigへのアクセス方法
かぬコンの設定は、Webconfigから行います。
Plusボタンを押しながらPCへ接続
[Link](http://192.168.7.1)にアクセス
# BOOTSELについて
Webconfigにアクセス
Rebootをクリック
USB(BOOTSEL)を選択
flash_nuke.uf2をドラックアンドドロップ
しばらく待つと再度ウインドウが表示される
GP2040-CE_0.7.1_WaveshareZero.uf2（ファイル名は変更されている可能性があります。）をドラックアンドドロップ
PCとかぬコンの接続を解除
# TILTボタンについて
かぬコンでは、スマブラ特有の動作をスティックを使わずに再現するためにTILTボタンを設定しています。
## Pin Mappingでは、方向キーは設定しない
Tiltの機能を使用する場合、Up,Down,Left,Rightの設定は、Add-Ons ConfigurationのTiltから設定を行います。
そのほかのボタンは、こちらで設定可能です。
## Add-Ons ConfigurationのTiltから方向キーを設定
## FunctionボタンとRight Analogを同時押しでHome,Minus,Plus,Captureが機能する
