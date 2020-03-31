# Hackintosh-EFI-For-Deskmini-310-i5-9400

## 前言
去年5月份购买过Deskmini A300，寻思装黑苹果，不过AMD的CPU折腾起来太麻烦，集成显卡也不支持。

所以新购置了Deskmini H310。

关于CPU考虑过i3-8100,四核四线程，不过内存只支持到2400，手头有2666的所以放弃了。
i5-8400,i5-8500一直想买，可惜缺货。 所以，决定购入i5九代。

先搬运：https://github.com/isNextJuly/Hackintosh-EFI-for-deskmini-310-i7-8700
的EFI试试看再调整。感谢isNextJuly。

## 更新
- 2020-03-31     
    - 更新WhateverGreen 1.3.8-t3测试版驱动，解决开机、睡眠黑屏问题
    (mushizhizhi提供，http://bbs.pcbeta.com/forum.php?mod=viewthread&tid=1850729&highlight=10.15.4%2B%BA%DA%C6%C1)

 - 2020-03-26     
    - 更新Clover 5107   
    - 更新WhateverGreen 1.3.8
    - 更新Lilu 1.4.3

## 配置：
 - CPU: i5-9400
 - 内存：金士顿 DDR4 2666MHz 8GB x 2
 - 硬盘：
      - Intel 760p 256G 
      - 西数固态Blue系列SATA3.0  500G  
      - 西数机械蓝盘 1TB 
 - 风扇：猫扇L9i
 - 无线网卡：BCM94352_DW1560_拆机卡
 - 显示器：
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

- 1.声卡 OK
- 2.网卡 Ok
- 3.蓝牙 OK
- 4.Airdrop OK  
- 5.接力 OK
- 6.App store  OK
- 7.睡眠 OK
- 8.USB&USB2.0扩展&Type C  OK   
- 9.双屏显示(待测试)
- 10.cpu 变频待测试  开启HWP 待测试
- 11.核显加速 待测试
- 12.Micro SD卡驱动  待解决
