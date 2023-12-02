## 机型配置如下
|硬件|厂商和配置|
|-|-|
|主板|ASUS ROG STRIX B660-A GAMING WIFI D4|
|CPU| Intel I5-12600K|
|内存| Kingston FURY 32GB(16G×2) DDR4|
|网卡|Intel 2.5G I225-v|
|WIFI|Intel Wi-Fi 6 AX 201 160MHz|
|声卡|ALC4080|
|显卡|蓝宝石RX 590 GME 8G D5 超白金极光特别版(为了免驱,刷了580的vbios) |
|硬盘1|Intel SSDPEKKW256G8 NVME|
|硬盘2|Samsung SSD 980 500G NVME|
|硬盘3|ST1000LM048-2E7172|
|硬盘4|ST1000LM048-2E7172|
|硬盘5|ST2000DM008-2FR102|
|硬盘6|ST2000DM001-1ER164|

**注意** 
- BIOS配置 

  -  关闭VT-d
  -  关闭CFG Lock
  -  关闭CSM
  -  关闭安全启动
  -  关闭快速启动

  其他的设置可参考网上的配置，这里不在赘述了。 

- 安装注意 

  如果USB3.0提示安装失败，多尝试一些USB2.0的接口试试。 

## 系统功能部分

- wifi

  测试正常

- 蓝牙
  
  测试正常

- 有线网卡

  测试正常

- 休眠

  测试正常，定义了UTBMAP.kext，配合USBToolBox.kext一起使用，不然单独使用UTBMAP.kext 启动系统很慢且进入系统后USB设备都会失效。

- USB

  除了后面的那个红色的USB口(图中的10口)不能用以外，其他的都正常工作，不是强迫症，反正也用不到，懒得搞了。
  
 ![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/IO.png)

## 没有搞定

内存这有叹号，另外2个槽也模拟了16G内存，但是叹号依旧，"关于本机" 这里一直挂着 "1个提醒"，这里不在深究了，不影响使用

![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/Memory_Alert.png)

## 系统部分截图

![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/SystemInfo.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/AboutInfo.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/Hardware.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/nvme.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/Ethernet.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/USB.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/WIFI.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/AudioDevice.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/HarkDisk.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/SystemDashboard.png)
![monterey](https://github.com/w55554/ROG-STRIX-B660-A-GAMING-WIFI-D4/blob/main/images/VideoProc_Converter.png)
