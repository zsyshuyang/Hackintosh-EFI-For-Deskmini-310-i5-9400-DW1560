
<img src="https://github.com/zsyshuyang/Hackintosh-EFI-For-Deskmini-310-i5-9400-DW1560/blob/master/DeskMini-310.png" width="336" height="280" />

# Hackintosh-EFI-For-Deskmini-310-i5-9400

## 前言

个人自用EFI文件，引用整理了诸多前辈的成果，详细见致谢名单。

## 更新

- 2020-04-21
    - 更新clover v5113

- 2020-04-11
    - 安装10.15.4补充更新，无痛升级。
    
- 2020-04-06
    - 更新Clover_v5108
    - 更新正式版Lilu_v1.4.3、WhatevenGreen_v1.3.8、AppleALC_v1.4.8
    - 更新VirtualSMC_v1.1.2、BrcmBluetoothInjector_v2.5.2.kext等

- 2020-03-31     
    - 更新WhateverGreen 1.3.8-t3测试版驱动，解决开机、睡眠黑屏问题(mushizhizhi提供)

 - 2020-03-26     
    - 更新Clover 5107   
    - 更新WhateverGreen 1.3.8
    - 更新Lilu 1.4.3

## 配置

 - CPU: i5-9400
 - 内存：金士顿 DDR4 2666MHz 8GB x 2
 - 硬盘：
      - Intel 760p 256G 
      - 西数固态Blue系列SATA3.0  500G  
      - 西数机械蓝盘 1TB 
 - 风扇：猫扇L9i
 - 无线网卡：BCM94352_DW1560_拆机卡
 - 显示器：
    - 优派23.6寸4K VX2478-4K-HD
    - 三星26.9英寸2K 144Hz 1800R曲面

## Bios设置（目前P4.4）

- Load UEFI Defaults(F9)
- Advanced
    - Onboard HD Audio: Enabled
    - USB Configuration, XHCI Hand-off, Enabled
    - Super IO Configuration, Serial Port, Disabled（必须）
- Security 
    - Secure Boot, Disabled(by default)
- CSM打开 ，仅UEFI

- 开启HWP（bios）设置
   - cpu 芯片组 -> CPU C STATE SUPPORT  ENABLED
   - CFG Lock   Disabled

## 工作状态

### 正常工作：

- 1.声卡 
- 2.网卡 
- 3.蓝牙 
- 4.Airdrop  
- 5.接力 
- 6.App store  
- 7.睡眠 
- 8.USB&USB2.0扩展&Type C    
- 10.cpu 变频测试 
- 11.核显加速 
- 12.H.264硬件解码、编码、视频处理
- 13.SATA SSD Trim
 
### 待测试解决

- 1.双屏显示 待测试
- 2.开启HWP  待测试
- 3.Micro SD卡驱动 待解决

## 工具软件

- [Clover Configurator](https://mackie100projects.altervista.org/download-clover-configurator/)
- [Hackintool](https://github.com/headkaze/Hackintool)
- [Kext Utility](http://cvad-mac.narod.ru/index/0-4)

## 使用说明

- 需重新生成三码

## 致谢

 - [acidanthera](https://github.com/acidanthera)
 - [daliansky](https://github.com/daliansky/)
 - [liminghuang](https://github.com/liminghuang/)
 - [isNextJuly](https://github.com/isNextJuly/)






















