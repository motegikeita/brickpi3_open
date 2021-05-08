# BrickPi3で遊んでみた記録
LEGO Mindstorms NXT component + BrickPi3(Dexter Industries) を使ったロボット遊びの記録。  
NXTのセンサーを活用した自律制御に加え、PS4コントローラを使ったマニュアルコントロールや、Node-REDを介したAmazon Alexaによる音声コントロールも実装。  
言語はPython2.7（たぶん） 
   
なおロボットはもう解体してしまったので、今後の更新はありません。  
実装の参考にされる場合、コンポーネントの配線設定等は適当に読み替えて自己責任でのご利用をお願いします。

## LEGO Robot 5th Unit(Unicorn)
by Keita Motegi

### ハードウェア構成

* シャシー：  
LEGO Mindstorms NXT Bricks

* インテリジェントブロック：  
RaspberryPi 3 Model B+  
Dexter Industries BrickPi3 Base Kit

* BrickPi3モーターポート：  
A: LEGO Mindstorms NXT インタラクティブサーボモータ （ステアリングコントローラ）  
B: LEGO Mindstorms NXT インタラクティブサーボモータ （エンジン）

* BrickPi3センサーポート：  
1: LEGO Mindstorms NXT 超音波センサー


### ソフトウェア基盤／開発環境

#### Raspbian for robot
https://www.dexterindustries.com/raspberry-pi-robot-software/

## Notes

### LEGO Robot consists of LEGO Mindstorms NXT components and Dexter Industries BrickPi.
Technology depends on:

#### BrickPi3
https://www.dexterindustries.com/BrickPi/  
https://github.com/DexterInd/BrickPi3  
Copyright (c) 2016 Dexter Industries  
Released under the MIT license (http://choosealicense.com/licenses/mit/).  
For more information, see https://github.com/DexterInd/BrickPi3/blob/master/LICENSE.md  

#### pyPS4Controller
https://pypi.org/project/pyPS4Controller/  
By Artur Spirin  
Released under the MIT license (http://choosealicense.com/licenses/mit/).  

#### Node-RED
https://nodered.org  
Copyright (c) OpenJS Foundation.  

#### Node-RED Alexa Home Skill Bridge
https://alexa-node-red.bm.hardill.me.uk  
By Ben Hardill  
