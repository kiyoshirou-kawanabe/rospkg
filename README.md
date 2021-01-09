# ロボットシステム学　課題2
___
## 概要
このリポジトリは上田隆一先生の[第10回講義]()で作成したコードを改変したものです。<br>
ランダムに1～200の数字を配信するパブリッシャを持つ[rand.py](https://github.com/kiyoshirou-kawanabe/mypkg/blob/main/scripts/rand.py)。
それを購読し素数か判別するサブスクライバを持つ[n_prime.py](https://github.com/kiyoshirou-kawanabe/mypkg/blob/main/scripts/n_prime.py)のふたつのコードを作成しました。<br>
___
## 動作環境
- Ubuntu
  - 20.04.1 LTS
- ROS
  - Noetic
___
## デモ動画
デモ動画は[こちら](https://youtu.be/FeTo19cilD0)から
___
## インストール方法
### ROS
  ROSセットアップに使用したスクリプトは[こちら](https://github.com/ryuichiueda/ros_setup_scripts_Ubuntu20.04_desktop)です。<br>

### ワークスペース
  [こちら](https://github.com/ryuichiueda/robosys2020/blob/master/md/ros.md)の資料を参考にワークスペースを作成しました。<br>
  
### パッケージ
  以下のコマンドを実行しパッケージをクローンしてください。<br>
  ```
  $ cd ~/catkin_ws/src
  $ git clone https://github.com/kiyoshirou-kawanabe/Ros_H.W.git
  ```
catkin_wsの下でcatkin_makeを行いビルドしてください。<br>
```
$ cd ~/catkin_ws
$ catkin_make
$ source ~/.bashrc
```
___
## 使用方法
以下のコマンドを実行してください。<br>
```$ roslaunch mypkg mypkg.launch```
___
## ライセンス
- ROS -[BSD 3-Clause License](https://github.com/kiyoshirou-kawanabe/mypkg/blob/main/LICENSE)
___
