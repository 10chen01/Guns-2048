# Guns-2048
一个2048的变体，用枪械名字取代传统2048的数字，更有乐趣。

比如M4A1,HK416,HK417,AK47之类著名枪械种类繁多。

努力取得核弹，结束游戏

枪械&2048迷们看过来!

## 枪械及对应的数字

这个你可以在`GunVal.js`这个文件中看见值和对的关系。

网页后的说明链接也有。

不过这里还是先说明一下吧，防止有些萌新看不懂JSON(~~不会看JSON还来这里~~)

|枪械名GUN|对应VALUE|
|--------|----------|
|RVL(左轮)|2|
|P1911|4|
|USP|8|
|SP(蝎式)|16|
|SMG5|32|
|SMG7|64|
|PP-19|128|
|AS-VAL|256|
|M16A4|512|
|ECHO|1024|
|AKM|2048|
|QBJ-95|4096|
|AWM|8192|
|Ballet|16384|
|BZK(火箭筒)|32768|
|ATO(核弹)|65536|

## 加倍奖励

除以上普通块以外，我们还特殊做了一种块。

所有普通块都能和加强块合并，并依照加强块的面值进行乘法操作

加强块合并形成更强的加强块

如下·

|NAME|VAL|
|----|----|
|GB(含毒弹)|1|
|APB(穿甲弹)|2|
|DB(达姆弹)|4|
|HTB(高温弹)|8|

这个关系也存储在一个叫`ButVal.js`的文件中

## 应用尚在开发，欢迎大家加入
