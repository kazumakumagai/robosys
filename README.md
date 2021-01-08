# robosys ロボットシステム学課題　提出場

課題１　デバイスドライバーの作成

～～LEDの点滅～～

## 概要
LED３つの点灯、消灯をubuntuで操作します。

### 環境
・OS: Ubuntu 20.04.1 LTS

#### 準備物
・raspberry pi 4
・LED　（Vf:2.0）　×３
・抵抗器　赤黒茶金　×３
・ジャンパー線　×４
・ユニバーサル基盤
##### 配線
GPIO25、GPIO8、GPIO７、Ground　を使用

###### 手順
・https://github.com/kazumakumagai/robosys.git　をubuntuにインストール
・cd myled でmakeし実行
・点灯　LED1 echo 1 > /dev/myled0   
　　　　LED2 echo 2 > /dev/myled0 
　　　　LED3 echo 4 > /dev/myled0
・消灯　LED1 echo 0 > /dev/myled0
　　　　LED2 echo 3 > /dev/myled0
　　　　LED3 echo 5 > /dev/myled0
    
### 動画　

　　　https://youtu.be/PRGty1X1Ot8
