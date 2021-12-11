# crc

crc 校验在物联网数据校验中经常使用，这里封装了crc8和crc16的计算方法。

#### install

`go get -u github.com/itmisx/crc`

#### example

````go
// crc8
var data = []byte{0x01,0x02}
crc8 := crc.Crc8(data)
// crc16
var data = []byte{0x01,0x02}
crc16 := crc.Crc16(data)
````
