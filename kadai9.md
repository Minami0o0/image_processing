課題９
====

## 概要

本稿では、メディアンフィルター、平滑化フィルタを適用し，ノイズ除去を体験した。

## 使用した画像

![Alt text](img/christmas tree.jpg "Optional title")

## 結果


![Alt text](img/9-1.png "Optional title")

図１　白黒濃淡

![Alt text](img/9-2.png "Optional title")

図２ ノイズ添付

![Alt text](img/9-3.png "Optional title")

図３ 平滑化フィルタを用いて雑音除去

　ノイズが除去されていることがわかる。


![Alt text](img/9-4.png "Optional title")

図４　メディアンフィルタを用いて雑音除去

　より原画像に近くノイズが除去されていることがわかる。

![Alt text](img/9-5.png "Optional title")

図5　任意のフィルター適用

　ノイズはなくなっているが全体的に曇りがかっているように見える。



## プログラムのソース

[kadai9.m](https://github.com/Minami0o0/image_processing/blob/master/lecture_image_processing-master/kadai9.m)


## 考察

移動平均フィルターは各画素の値を、周辺画素の平均値に置き換える処理である。この処理をすると、全体的にエッジがなまった画像が生成される。メディアンフィルターは、各画素の値を周辺画素の中央値に置き換える処理である。この処理は、移動平均フィルターと比べて入力画像のエッジを損なわない画像が得られる。

どちらのフィルターでもきれいにノイズ除去ができていた。
