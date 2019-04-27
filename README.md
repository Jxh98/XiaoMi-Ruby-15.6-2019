# XiaoMi-Ruby-15.6-2019
## This is a repository of Hackintosh EFI/Clover files about the [MI laptop Ruby 2019](https://www.mi.com/mibook/ruby15-2019mx110/specs/).<br/>这是一个关于 [小米笔记本 Ruby 2019 款](https://www.mi.com/mibook/ruby15-2019mx110/specs/) 的 黑苹果 EFI/Clover 文件的存储库。

### 标准电脑配置

| 规格     | 详细信息                                   							  	|
| -------- | -----------------------------------------------------------				|
| 电脑型号 | 小米笔记本 Ruby 15.6" 2019款 集显款(UHD 620) / 独显款(UHD 620 + MX 110)		|
| 处理器   | Intel(R) Core(TM)  i3-8130U / i5-8250U / i7-8550U 							|
| 内存     | SK hynix 8GB/16GB DDR4 2400MHz												|
| 硬盘     | KINGSTON MS80000058688  (238 GB)	M.2(SATA)								|
| 集成显卡 | Intel(R) UHD Graphics 620  (1 GB)           			   					|
| 显示器   | 中电熊猫 ID	NCP002A 1920x1080 IPS 15.6"									|
| 声卡     | Realtek ALC256 (M) (节点:?) 												|
| 网卡     | 无线：Realtek RTL 8821CE	有线：Realtek RTL 8168B							|
| 触控板   | I2C HID 																	|
| 照相机   | XiaoMi USB 2.0 WebCam 														|
| 读卡器   | Realtek USB 2.0 Card Reader 												|

### 我的电脑配置

| 规格     | 详细信息                                   							  	|
| -------- | -----------------------------------------------------------				|
| 电脑型号 | 小米笔记本 Ruby 15.6" 2019款 独显款(UHD 620 + MX 110)      				|
| 处理器   | Intel(R) Core(TM) i5-8250U                      							|
| 内存     | SK hynix 16GB DDR4 2400MHz												|
| 硬盘     | KINGSTON MS80000058688  (238 GB)	M.2(SATA)								|
| 集成显卡 | Intel(R) UHD Graphics 620  (1 GB)           			   					|
| 显示器   | 中电熊猫 ID	NCP002A 1920x1080 IPS 15.6"									|
| 声卡     | Realtek ALC256 (M) (节点:?) 												|
| 网卡     | 无线：Qualcomm AR956x (DW1707)	有线：Realtek RTL 8168B						|
| 触控板   | I2C HID 																	|
| 照相机   | XiaoMi USB 2.0 WebCam 														|
| 读卡器   | Realtek USB 2.0 Card Reader 												|


## 介绍
搞了一周时间，终于搞定了部分功能。
实在是个人能力有限。 下面说一下 可以工作的部分  和  不能工作的部分。
更换了无线网卡。
最后希望有大佬能完善一下。

### 可以工作

#### 核显
不驱动 的话（7m） 内屏显示正常 外接屏幕不显示
驱动 的话  内屏第一次开机不显示 外接屏幕显示正常  （睡眠一次 内屏显示正常）
驱动方法 仿冒 HD 620 即可
#### 无线
正常驱动 驱动方法见 (我的博客)[https://jxh98.github.io/2019/04/18/Hackintosh/]
#### 有线
正常驱动
#### 蓝牙
从Windows / Linux 启动 可正常使用 冷启动无效
#### 电量
电量显示正常 充电状态正常
#### 声卡
耳机插孔有声音   扬声器没声音
#### 开机 关机 重启
正常
#### 睡眠
未详细测试  （一般测试可唤醒）
#### 键盘
正常工作 ， 不能触摸触控板 。否则 内置键盘失效
#### USB接口 
大概正常

### 不能工作

#### 触控板 I2C
尝试驱动未成功

#### 扬声器 ALC256 (M)
尝试驱动未成功

#### AirPort
尝试驱动未成功




