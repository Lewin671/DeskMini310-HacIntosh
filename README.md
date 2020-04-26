# DeskMini 310 Hackintosh

### Specs

+ macOS Catalina 10.15.4
+ OpenCore 0.5.7
+ DeskMini 310
+ Bios version 4.20
+ Intel core i3-8100
+ 海盗船 16Gb内存条
+ 东芝 SATA TR200 250GB
+ 东芝SATA机械硬盘 500GB
+ CS2原装网卡

### Bios settings

+ Advanced > Chipset Configuration > Above 4G Decoding: Enabled
+ Advanced > Chipset Configuration > Onboard HD Audio & Onboard HDMI HD Audio: Enabled
+ Advanced > Chipset Configuration > VT-d: Disabled
+ Advanced > USB Configuration > XHCI Hand-off: Enabled
+ Advanced > CPU Configuration > C States Support: Disabled
+ Advanced > Security > Secure Boot: Disabled
+ BOOT > CSM: Enabled

### What's working

+ Sleep
+ Handoff, Sidecar, iServices
+ WiFi and Bluetooth without patching
+ Video acceleration

### Some important stuff

+ Don't copy the EFI blindly, you could harm your system
+ Use the Desktop Guide to tailor your own EFI, matching your setup
+ OpenCore logging is disabled, you should enable it for troubleshooting
+ Change the platform info when your done installing to enable iServices
+ 把"config.plist副本"的"副本"去掉。


### Geekbench 5

+ CPU: https://browser.geekbench.com/v5/cpu/1917142
+ OpenCL: https://browser.geekbench.com/v5/compute/811443 

### 日志

- 2020.4.26: 切换到OpenCore 5.7，解决了帧缓冲导致内核崩溃重启的问题 

