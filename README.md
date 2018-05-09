# hacksweeper

##esp8266
motor test 的代码，内存太小， 切换到d1,但是d2,d3  ab 检测不能工作
和 i2c 冲突


##esp8266 router 模式
###router login 与 motor i2c 代码冲突，如果长时间无法登过到网络，motor  stack trace overflow
###router login 与 i2c lcd 冲突， 先初始化 i2c ,  router login 失败


### d1 mini connect arduino motor shield , 各自独自供电：5v,gnd 接通 ，scl,sda 接通。
   vin 不知道如何接。但是 arduino 如果对接了vin , 可以分享供电。
   
