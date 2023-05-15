# この説明書はGP2040-CEの補足資料
この説明書は、かぬコンで追加した機能に関する部分のみ説明します。

詳しい使い方は、[GP2040-CE](https://gp2040-ce.info/#/)　をご確認ください。

# Webconfigへのアクセス方法
かぬコンの設定は、Webconfigから行います。

Plusボタンを押しながらPCへ接続（デフォルトのPlusボタンは画像の位置です。）

<img src="button-s2.jpg" width="300">

[Link](http://192.168.7.1)にアクセス
# ファームウェアの更新方法について
Webconfigにアクセス

<img src="web-home.jpg" width="600">

Rebootをクリック

<img src="web-home-1.jpg" width="600">

USB(BOOTSEL)を選択

<img src="web-reboot-01.jpg" width="600">

flash_nuke.uf2をドラックアンドドロップ

<img src="rpo-rp2.jpg" width="600">

しばらく待つと再度ウインドウが表示される

GP2040-CE_0.7.1_WaveshareZero.uf2（ファイル名は変更されている可能性があります。）をドラックアンドドロップ

PCとかぬコンの接続を解除

# TILTボタンについて
かぬコンでは、スマブラ特有の動作をスティックを使わずに再現するためにTILTボタンを設定しています。

Tilt1よりTilt2のほうがスティックの傾きがより小さくなります。

### tilt1
<img src="tilt1-01.jpg" width="300">


### tilt2
<img src="tilt2-01.jpg" width="300">

Tiltボタンを押しながら、Right Analogを押すことで上下にシフトさせることができます。
## Pin Mappingでは、方向キーは設定しない
Tiltの機能を使用する場合、Up,Down,Left,Rightの設定は、Add-Ons ConfigurationのTiltから設定を行います。

<img src="web-config-01.jpg" width="600">

そのほかのボタンは、こちらで設定可能です。

<img src="web-pin-mapping.jpg" width="600">

## Add-Ons ConfigurationのTiltから方向キーを設定

<img src="web-config-addon-01.jpg" width="600">

Left Analog（Lスティック）とRight Analog(Cスティック)の設定をしてください。

<img src="web-pin-mapping.jpg" width="600">
## FunctionボタンとRight Analogを同時押しでHome,Minus,Plus,Captureが機能する
Functionボタンは、Right Analogと同時押しすることで、Home,Minus,Plus,Captureが機能します。

### Plus

<img src="func2-01.jpg" width="300">

### HOME

<img src="func1-01.jpg" width="300">

### Capture

<img src="func3-01.jpg" width="300">

## Minus

<img src="func4-01.jpg" width="300">

試合中に押すことで、試合が中断する可能性のあるボタンを押しにくくしました。

## Tilt1ボタンとTilt2ボタンを同時に押すことで、Right AnalogがD-Padとして機能する

<img src="dpadr-01.jpg" width="300">

<img src="dpadd-01.jpg" width="300">

<img src="dpadu-01.jpg" width="300">

<img src="dpadl-01.jpg" width="300">
