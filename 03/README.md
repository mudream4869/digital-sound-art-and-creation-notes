# 20190311

## 複習上節課

Files:
* `piano.pd`: 輸入琴鍵編號，輸出鋼琴聲音（從按下去到彈起來）
* `main.pd`:
和弦操作
![](https://i.imgur.com/WNaLFEY.png)

## 使用 Message 製作和弦

在使用之前要先設定按鈕的屬性裡面的「Receive Symbol」。

![](https://i.imgur.com/iDSuUQ5.png)

## QList

![](https://i.imgur.com/kSAgGkF.png)

```
時間毫秒 目標名稱 指令;
```

```
0 chord-1 bang;
1000 chord-2 bang;
1000 chord-1 bang;
```

## Echo and Reverb

* delread: Delay Read Buffer
* delwrite: Delay Write Buffer

![](https://i.imgur.com/Lw7THAx.png)

## Abelton

### spigot

藉由 toggle 來控制 bang 訊號可否通過

![](https://i.imgur.com/mSCFEe1.png)
