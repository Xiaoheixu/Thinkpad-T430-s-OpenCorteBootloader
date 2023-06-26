![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ic1gkvrxj21340u0gqm.jpg)

中文指南：[https://github.com/xiaoheixu/thinkpad-t430-s-poportebootloader/main/readme.md](https://github.com/Xiaoheixu/Thinkpad-T430-s-OpenCorteBootloader/blob/main/README.md)

QQ Q/A Group：1095397835

The purpose of this project is to allow the Lenovo ThinkPad T430 series laptop to use MacOS.

Note: This series of laptops has a WiFi card whitelist, and you cannot change any network card.

Unlock BIOS whitelist tutorial:

1：https://post.smzdm.com/p/a4wmd65x/

2.https://bbs.ibmnb.com/forum.php?mod=viewthread&tid=1944574&highlight=T430

Unlock BIOS whitelist tool:

Link: https://pan.baidu.com/s/1nH9T15mmnlaNBmUhuUHuAg

Extract code: BPVJ

Blog link: https://macpc.top (Temporaraly shutdown, expected to reopen in October)


## My configuration:
| Hardware     | Hardware      |
|----------|:-------------------------|
| CPU     | i5-3320M/i7-3632QM                 |
| RAM     | 8*8 Dual Channel                |
| HD    | 240G MSATA     |
| Network Card     | Bcm94360HMB/Bcm943224HMP |
| Bluetooth    | Bcm20702A0               |
| Graphics    | HD4000                   |
| Version | 10.15.7～12.2Beta1        |


## Supported Versions

MacOS Ventura13.x  
MacOS Monterey 12.x  
MacOS Big Sur 11.x  
MacOS Catalina 10.15.x  
MacOS Mojave 10.14.x  
MacOS High Sierra 10.13.6 (17G65)


## Recommended Image:
| Easy | Needs some Work | Difficult |
|--------------|:-------------|:-------------|
|10.1x.x| 12.x/13.x.x    |None    |

## Compatable Model

- T430/T430s

## Releases

The final version is v0.1.1 to [Release Page](https://github.com/xiaohehexu/thinkpad-t430-s-opencortelateloader/releases/tag/t430-0.8.6.1).

## Requirements
-The downloaded MacOS image (supports Macos High Sierra (10.13.6) - Macos Macos Ventura installation)

-16GB USB Drive

## BIOS Settings
-Achi mode

-CSM closed

-TV-D Close

-Entreate BIOS version (Xiaobai, please do not operate)

-Base UEFI mode

-Card the independent graphics card

-Staches safety start.
## What works

-Uefi Start through CLOVER/OC

-System Updates

-Built-in keyboard

-USB3.0/USB2.0 Ports

-Native audio, including headphones

-Built-in camera

-Power management

-Battery status

-Ethernet Card

-Mac App Store/Apple ID

-CPU frequency

-Waking up from sleep (mouse, keyboard, power keys wake up normal)

-WI-FI (replaced BCM943602CDP)

-Bluetooth (replace BCM943602CDP)

-Tata panel (some gesture support)

-IMESSAGE/FACETIME

## What doesn't work
-VGA mini DP microphone, because the mini DP is connected to the disabled NVIDIA professional card, it is impossible


## About the Author

The author is still a hard-working student. The update may be slower, but I can do my best. I may not be satisfied with many people, but I will try to do it.

![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ictm8olyj20af0ah0ti.jpg) 

![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ics9jv5hj20h00h0dhf.jpg) 

## Thanks

Thanks [Apple] (https://www.apple.com/) provided macOS.

Thanks for [acidanthera] (https://github.com/acidanthera) provided the core drivers.

Thanks [dortania] (https://github.com/dortania) provided the HD4000 driver for the HD4000

Thanks for [Daliansky] (https://github.com/daliansky) provided OC-LITTLE

Thank you [OpenCore part library] (https://ocbook.tlhub.cn/?q=) provided OpenCore

Thanks [zhen- zen] (https://github.com/zhen-zen) provided  Yoga SMC

Thanks [zxystd] (https://github.com/openintelwireless) provided the Intel Wi-Fi driver
