## 概要

本稿では、白黒濃淡画像にしたのち、２・４・８段階画像に変換した。

## 使用した画像

![Alt text](1-1.png "Optional title")

## 結果


![Alt text](1-2.png "Optional title")

図１　白黒濃淡

![Alt text](1-3.png "Optional title")

図２ 64


![Alt text](1-4.png "Optional title")

図3　96

![Alt text](1-5.png "Optional title")

図4 128

![Alt text](1-6.png "Optional title")

図5　192


### 他の画像で試した

![Alt text](hashi.png "Optional title")

図6　hashi.png

![Alt text](kadai3/21.png "Optional title")

図7 白黒濃淡

![Alt text](kadai3/22.png "Optional title")

図8 64

![Alt text](kadai3/23.png "Optional title")

図9 96

![Alt text](kadai3/24.png "Optional title")

図10 128

![Alt text](kadai3/25.png "Optional title")

図11 192



## プログラムのソース

[kadai3.m](https://github.com/shimamurakie/ImageProssessing/blob/master/kadai3.m)

## 説明

## 考察
nuko.pngは猫の輪郭がはっきりしていないせいか、どの閾値をとっても画像が不明瞭となってしまった。

一方hashi.pngでは輝度のバランスが良く、木の葉による影ご細かいことから64の閾値でくっきりとした画像となった。


## Contribution



## Author

[shimamurakie](https://github.com/shimamurakie)
