課題２
====

## 概要

本稿では、白黒濃淡画像にしたのち、２・４・８段階画像に変換した。

## 使用した画像

![Alt text](img/christmas tree.jpg "Optional title")

## 結果


![Alt text](img/2-1.png "Optional title")

図１ 白黒濃淡画像

![Alt text](img/2-2.png "Optional title")

図２　２段階調

![Alt text](img/2-3.png "Optional title")

図３　4段階調

![Alt text](img/2-4.png "Optional title")

図４　8段階調


## プログラムのソース

[kadai2.m](https://github.com/Minami0o0/image_processing/blob/master/lecture_image_processing-master/kadai2.m)

## 説明

    IMG0 = ORG>32;
    IMG1 = ORG>64;
    IMG2 = ORG>96;
    IMG3 = ORG>128;
    IMG4 = ORG>160;
    IMG5 = ORG>192;
    IMG6 = ORG>224;
    IMG7 = ORG>256;
    IMG = IMG0 + IMG1 + IMG2 + IMG3 + IMG4 + IMG5 + IMG6 + IMG7;

輝度値32から256まで、32ごとに閾値をとって2値化し、最後に加算して表示した。

## 考察

どちらの画像においても、8段階画像で被写体が識別可能となる状態になっている。

このようにしてポスタリゼーションを行うことで、画像のサイズを小さくすることができる。
