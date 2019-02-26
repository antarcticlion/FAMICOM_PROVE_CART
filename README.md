# FAMICOM_PROVE_CART
Famicom 60pin cartridge Probing Board. (For Logic analyzer / Oscilloscope / Multimeter / etc.)

## 概要

ファミコンの60ピンカートリッジバスの信号をモニターするための基板です。  
プロジェクトにはKiCad PCB 5.0用のプロジェクトファイルとガーバーが含まれます。

![Probing board](https://github.com/antarcticlion/FAMICOM_PROVE_CART/blob/master/probing%20board_001.jpg)

## 作り方

ボードを基板製造業者に発注する場合、1.2mm厚で注文してください。  
基板上部に2.54mmピッチ60ピンのカードエッジソケットを半田付けします。  
ボード中央のスルーホールは、使用する測定機材にあわせて、ピンヘッダやテストピンを半田付けしてください。

## 使い方
ファミコン本体とカートリッジ間に設置します。  
「FRONT SIDE」と書かれた方が正面です。  
正面から見て左下が1番ピン、左上が2番ピン、右下が59番ピン、右上が60番ピンです。

![Board Settings](https://github.com/antarcticlion/FAMICOM_PROVE_CART/blob/master/probing_boad_settings_001.jpg)

標準より重心が高くなりますので、ディスクシステム用RAMカートリッジ等の大きめカートリッジは不安定になりますので注意してください。


（このボードを使用してキャプチャした信号のサンプル：PRG-ROM側の制御線、アドレス線上位）
![Captude signal sample](https://github.com/antarcticlion/FAMICOM_PROVE_CART/blob/master/probing_board_capture_sample.jpg)

## Lastest Gerber

Rev 0.1 fix 1
https://github.com/antarcticlion/FAMICOM_PROVE_CART/blob/master/gerber_FAMICOM_PROVE_CART01B.zip


## Changes Log  
 -Rev 0.1 fix 1 2019/02/26  
  -Typo fix  
 -Rev 0.1       ファーストリリース 2019/02/26  


## ライセンス
クリエイティブコモンズ　表示 - 継承 4.0 国際 (CC BY-SA 4.0)

https://creativecommons.org/licenses/by-sa/4.0/  
https://creativecommons.org/licenses/by-sa/4.0/legalcode
