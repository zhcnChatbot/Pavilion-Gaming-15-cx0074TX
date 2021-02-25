# 光影精灵4 i5-8300H clover EFI

****已确认工作****

Intel graphic UHD 630 可以正常驱动

正常调节亮度，记忆亮度信息

144hz 刷新率可调

有线上网，无线上网（ clover 版本需要软件支持），蓝牙

内置键盘，触控板，键盘灯及开关

蓝牙耳机，type-c 耳机，外放正常工作 （注入 ID 为 28，其他为）并可以通过键盘上的快捷键快速调节

前置摄像头工作正常（tested via FaceTime）

****已知问题****

休眠时风扇会转动，不是真正休眠

HDMI 接口暂时不可用，可用 type-c 转 USB 代替

Android USB 网络共享暂不可用

Nvidia 独立显卡已被屏蔽

****其他注意事项****

开机后有极小概率出现小于 0.1s 的雪花屏

容器不可扩容，苹果系统问题

如果遇见 开机后外置扬声器没有生意的情况，请首先检查注入之 驱动 ID。如果都不行，请将 /EFI/CLOVER/kexts/Others/CodecCommander.kext 备份到别处

键盘暂时无法调整亮度

****感谢****

https://github.com/mechtifs/hackintosh-hp-15-cx0/ 

https://github.com/acidanthera/AppleALC

https://github.com/acidanthera/virtualsmc/

