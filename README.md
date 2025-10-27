# ラズベリーパイ4にUbuntu Desktop 22.04をインストールし、ROS2 Humble環境を構築する手順

1. PCへraspberry pi imagerをインストール

https://www.raspberrypi.com/software/

2. microSDカードをPCへ接続

3. raspberry pi imagerを起動し、ラズベリーパイの型式、入れるOS、ストレージを選択し書き込み

4. 書き込みが完了したら、microSDカードをラズベリーパイ4へ装着

5. 電源をつなぎ、Ubuntu Desktop 22.04を起動

6. キーボード操作で初期設定

7. ssh設定を有効化する

過程で起こったこと

1. network-configとuser-dataをmicroSDに書き込んで起動したが、動作がおかしくなった。

2. 電源をpoweroffで切ったが、microSDが読み込めなくなった。

3. sd formatterでクイックフォーマットして何とかなった。しかし、一歩間違えば破損させてしまうところだったので注意したい。
