
# `ZJ` f063 : The Strongest Chain 最強鏈條

標籤：null
題目來源：[ZeroJudge f063](https://zerojudge.tw/ShowProblem?problemid=f063)
題目出處：板橋高中教學題 [管理者： snail (蝸牛)]

## Problem 題目

英文有一句諺語: "A chain is only as strong as its weakest link." (一條鐵鍊的強度相當於其中最弱的一環。) 用來說明一個團隊中的最弱的一個人足以拖垮整個團隊的表現，也就是俗稱的「豬隊友」。

給你若干條鐵鍊中每條鐵鍊的每個環節的強度，請找出最強的鍊條。

* 輸入說明：輸入的第一行含有一個整數 n，代表鐵鍊的數量。接下來有 n 行，每行代表一條鐵鍊，第一個整數 k 代表這條鍊條有幾個環節，其後有 k 個整數代表每個環節的強度。
* 輸出說明：輸出最大的鍊條強度。

## Sample 測資範例

### #1

|Input:
|:-|
|2<br>3 15 17 19<br>4 43 37 28 11

|Output:
|:-|
|15

### #2

|Input:
|:-|
|4<br>4 10 11 8 9<br>5 15 12 18 7 20<br>3 16 20 22<br>3 123 23 3

|Output:
|:-|
|16

## 測資資訊
參考：題目來源

## 提示：
* Null

## 題意
找出每條鐵鍊的最小值
最後求出這些最小值中的最大值 即是答案
