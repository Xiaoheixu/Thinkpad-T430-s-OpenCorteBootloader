![image](https://tva1.sinaimg.cn/large/e6c9d24ely1h4ic1gkvrxj21340u0gqm.jpg)

##Overview



Q&A group: 1095397835



The purpose of this project is to enable the LENOVO ThinkPad T430 series notebook to use MacOS.



Note: This series of laptops has a WiFi whitelist and cannot be replaced with any network card,



Unlock bios whitelist tutorial:



1: https://post.smzdm.com/p/a4wmd65x/



two https://bbs.ibmnb.com/forum.php?mod=viewthread&tid=1944574&highlight=T430



Unlock bios whitelist tool:



Link: https://pan.baidu.com/s/1nH9T15mmnlaNBmUhuUHuAg



Extract code: bpvj



Blog link: https://macpc.top (Currently closed and expected to reopen in October)




##My configuration:

|Hardware | Hardware|

|----------|:-------------------------|

|CPU | i5-3320M/i7-3632QM|

|Memory | 8 * 8 dual channel|

|Hard Disk | 240G Taiwan/1T Misbranded Msata|

|Network card | Bcm94360HMB/Bcm943224HMP|

|Bluetooth | Bcm20702A0|

|Graphics Card | HD4000|

|System version | 10.15.7~12.2Beta1|




##Applicable system



MacOS Ventura13. x

MacOS Monterey 12. x

MacOS Big Sur 11. x

MacOS Catalina 10.15. x

MacOS Mojave 10.14. x

MacOS High Sierra 10.13.6 (17G65)




##Recommended image:

|No special operations required | Special operations required | Currently difficult to deliver|

|--------------|:-------------|
|10.1x.x| 12.x/13.x.x    |None    |


##Applicable models



-T430/T430s



##Publish



The final released version is v0.1.1, go to the [Release Page]（ https://github.com/Xiaoheixu/Thinkpad-T430-s-OpenCorteBootloader/releases/tag/T430-0.8.6.1 ）.



##What is needed

-Downloaded MacOS image (supports image installation for macOS High Sierra (10.13.6) - macOS MacOS Ventura)

-16GB USB drive



##BIOS Ensure Settings

-ACHI mode

-CSM Off

-TV-D off

-Upgrade BIOS version (do not operate Xiaobai)

-Enable UEFI mode

-Shield independent graphics card

-Disable secure startup.

##Functionality for normal operation

-UEFI starts through Clover/OC

-Support OTA upgrade to the latest system for any version

-Built in keyboard

-Native USB 3.0/USB 2.0

-AppleHDA native audio, including headphones

-Integrated camera

-Power management

-Battery status

-Backlight control

-Nuclear display driver

-Wired Ethernet card

-Mac App Store Apple ID is running normally

-CPU frequency conversion

-Sleep wake-up (mouse, keyboard, and power button wake-up are all normal)

-Wireless network (replace Bcm943602cdp)

-Bluetooth (replace Bcm943602cdp)

-Touchpad (some gesture support)

-IMessage/FaceTime



##Functions that cannot be used normally

-The VGA MINI DP microphone cannot provide image output due to its connection to a disabled Nvidia professional card (note for standalone versions). The VGA world has no solution, and the microphone has current sound in the macOS Monterey system




##About feeding



The author is still a struggling student on campus, and updates may be slower. However, I try my best and may not be able to meet the needs of many people, but I will try my best to do a good job



! [image]（ https://tva1.sinaimg.cn/large/e6c9d24ely1h4ictm8olyj20af0ah0ti.jpg ）



! [image]（ https://tva1.sinaimg.cn/large/e6c9d24ely1h4ics9jv5hj20h00h0dhf.jpg ）




##Acknowledgement



Thank you [apple]（ https://www.apple.com）

Thank you [acidanthera]（ https://github.com/acidanthera ）The vast majority of core drivers provided
Thank you [dortania]（ https://github.com/dortania ）Provided patch driver for HD4000
Thank you [daliansky]（ https://github.com/daliansky ）OC title provided
Thank you [OpenCore Part Library]（ https://ocbook.tlhub.cn/?q= ）OpenCore components provided
Thank you（ https://github.com/zhen-zen ）Yoga SMC provided
Thank you [zxystd]（ https://github.com/OpenIntelWireless ）Intel WI-FI driver provided
