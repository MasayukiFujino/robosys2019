# robosys2019

# ライセンス概要

This repository is licensed under the BSD-3-Clause license, see LICENSE.

# 課題概要

講義で利用したプログラムになります。<br>
Tera Termを3つのウィンドウで開き,<br>

$rosrun mypkg count.py <br>

$rourun mypkg twice.py <br>

$rostopic echo /twice <br>

以上の3種類のコマンドを一つのウィンドウにつき一つ実行すると,　<br>
$rostopic echo /twice を実行したウィンドウで,<br>
count_upから出された値を2倍したものをどんどん足し合わせて表示します。<br>

# ファイルの位置

$/catkin_ws/src/mypkg/scripts/count.py <br>
$/catkin_ws/src/mypkg/scripts/twice.py <br>

# 操作方法

$ make <br>
$ sudo insmod myled.ko <br>
$ sudo mknod /dev/myled0 c 240 0 <br>
$ sudo chmod 666 /dev/myled0 <br>
$ echo 1 > /dev/myled0 <br>
$ echo 2 > /dev/myled0 <br>
$ echo 3 > /dev/myled0 <br>
$ echo 4 > /dev/myled0 <br>

# 動画URL
