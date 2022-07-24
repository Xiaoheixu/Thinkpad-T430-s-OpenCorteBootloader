![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ic1gkvrxj21340u0gqm.jpg)

## 概述

疑问解答QQ群：1095397835

本项目的目的是让 LENOVO Thinkpad T430系列笔记本使用上 MacOS。

注意：此系列笔记本电脑有WiFi白名单， 不可以更换任意网卡，

解锁bios白名单教程：
1：https://post.smzdm.com/p/a4wmd65x/

2.https://bbs.ibmnb.com/forum.php?mod=viewthread&tid=1944574&highlight=T430

解锁bios白名单工具：链接：https://pan.baidu.com/s/1nH9T15mmnlaNBmUhuUHuAg
提取码：bpvj

博客链接：https://macpc.top(目前处于关停状态预计在10月份将再次开通）


## 我的配置：
| 硬件      | 硬件      |
|----------|:-------------------------|
| CPU     | i5-3320M/i7-3632QM                 |
| 内存     | 4*4双通道                |
| 硬盘     | 240G台电/1T杂牌Msata     |
| 网卡     | Bcm94360HMB/Bcm943224HMP |
| 蓝牙     | Bcm20702A0               |
| 显卡     | HD4000                   |
| 系统版本 | 10.15.7～12.2Beta1        |


## 适用系统

MacOS Monterey 12.x  
MacOS Big Sur 11.x  
MacOS Catalina 10.15.x  
MacOS Mojave 10.14.x  
MacOS High Sierra 10.13.6 (17G2112)


## 推荐镜像：
| 无需特殊操作 | 需要特殊操作 | 目前难产 |
|--------------|:-------------|:-------------|
|10.1x.x| 12.x    |13.x    |


## 适用型号

- T430/T430s/T430i

## 发布

最后发布的版本是 0.8.3前往 [Release Page](https://github.com/Xiaoheixu/Thinkpad-T430-s-OpenCorteBootloader/releases/tag/T430-0.8.3) 。

## 需要什么
- 下载好的 MacOS 镜像（支持 macOS High Sierra (10.13.6) - macOS MacOS Monterey 的镜像安装）
- 16GB U盘

## BIOS确保设置
- ACHI模式
- CSM关闭
- TV-D关闭
- 升级BIOS版本（小白请勿操作）
- 启用UEFI模式
- 屏蔽独立显卡
- 禁用安全启动。
## 正常工作的功能
- UEFI通过 Clover/OC 启动
- 支持任意版本系统OTA升级到最新系统
- 内置键盘以及数字键盘
- 原生USB3.0/USB2.0 
- AppleHDA原生音频，包括耳机
- 内置摄像头
- 原生电源管理
- 电池状态
- 背光控制
- 核显驱动
- 有线以太网卡
- Mac App Store Apple ID正常运行
- CPU变频
- 睡眠唤醒（鼠标，键盘、电源键唤醒均正常）
- 无线网络（更换Bcm94360cdp）
- 蓝牙（更换Bcm94360cdp）
- 触控板 （部分手势支持）
- 随航（有线/无线）
- iMessage/FaceTime

## 不能正常使用的功能
- VGA MINI DP 麦克风，因MINI DP 连接到已禁用的Nvidia专业卡，无法提供图像输出（独显版需要注意）VGA世界无解，在macOS Monterey里面麦克风有电流声 以下系统没有


## 关于投喂

作者还是个苦逼在校生，更新可能会慢一些 但是我我尽力 ，可能无法做到很多人满意 但我会尽量去做好 

| 微信                                                       | 支付宝                                               | |                                                    
| ---------------------------------------------------------- | ---------------------------------------------------- | 
| ![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ictm8olyj20af0ah0ti.jpg) | ![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ics9jv5hj20h00h0dhf.jpg) | 
## 致谢

感谢 [apple](https://www.apple.com.cn/) 提供的 MacOS  

感谢 [acidanthera](https://github.com/acidanthera) 提供的绝大部分核心驱动 

感谢 [dortania](https://github.com/dortania) 提供的HD4000的修补程序驱动 

感谢 [daliansky](https://github.com/daliansky) 提供的OC-little

感谢 [OpenCore部件库](https://ocbook.tlhub.cn/?q=) 提供的OpenCore部件

感谢 [zhen-zen](https://github.com/zhen-zen)提供的Yoga SMC

感谢 [zxystd](https://github.com/OpenIntelWireless)提供的Intel WI-FI驱动
