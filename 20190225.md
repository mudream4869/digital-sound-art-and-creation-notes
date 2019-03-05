# 20190225

* PureData
* Manual: [:book: FLOSS PureData](http://booki.flossmanuals.net/_booki/pure-data/pure-data.pdf)

## Normal

* print, int, +, %
* metro: 每固定時間發出訊號
* toggle, bang: 按鈕

## Digital Analog Converter

### 發出 f = 440 的波到兩個發聲器
![](https://i.imgur.com/tiZgpc2.png)

### 樂器：![](https://i.imgur.com/PkT73Hd.png)
特雷門
控制聲量和音高
![](https://i.imgur.com/7vIPFJm.png)

### 顯示波型: tabwrite + array
![](https://i.imgur.com/nOc0nDD.png)

### 麥克風接 dac
左右分別代表聲道
![](https://i.imgur.com/CPIhQBq.png)

### 錄音錄到 array
![](https://i.imgur.com/4grOW7y.png)

### 播放 array
* 直接播放
![](https://i.imgur.com/uWBx3Mb.png)

* 區間播放：指定起點終點和取樣數
`[起點, 終點, 取樣數]`
![](https://i.imgur.com/ByS6SBf.png)

ex: 爬說語
