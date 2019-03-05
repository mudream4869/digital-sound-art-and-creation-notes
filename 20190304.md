# 20190304

* purr-data: 更多功能

## phasor

phasor 會提供一個 $f(x) = \{x\}$ 的振盪器。

![](https://i.imgur.com/w5sktOF.png)

### 可以用這個做出**方波**

使用 `expr~`:

![](https://i.imgur.com/MwVcQfI.png)

調整 0.5 到 0.1 或 0.01 可以模擬出彈喇吧膜的聲音。

## 自訂波形

`tabread4` 是 `tabread` 的 quadric interpolation 版本。

![](https://i.imgur.com/7DvwYuU.png)

## Overtone

![](https://i.imgur.com/CCtDtQv.png)

## 畢式音律

* 小提琴和鋼琴不太一樣
* 12 平均率
* 三分損益法
* 琴鍵 to 頻率


![](https://i.imgur.com/QqcIqfB.png)

## 把程式包進一個小視窗

* `pd name`
* inlet 是 input 參數
* output 是 output 參數
* 參數後面加 `~` 是指訊號

![](https://i.imgur.com/HDptRzU.png)

## 琴鍵模擬

![](https://i.imgur.com/ENmpNIT.png)

`trigger` 可以協助把訊號的先後順序處理好，先右後左。

![](https://i.imgur.com/JegJQ1s.png)

最後整合一下，合成器：

![](https://i.imgur.com/bR4NKvG.png)

## ADSR

音樂四階段變化：

* Attack
* Decay
* Sustain
* Release

![](https://i.imgur.com/9qhoemA.png)
![](https://i.imgur.com/5rKaWJs.png)

## select + key

![](https://i.imgur.com/m4LF0tR.png)

## 音效

* Mario 音效

![](https://i.imgur.com/G7FX10J.png)
![](https://i.imgur.com/ls7Wmis.png)
