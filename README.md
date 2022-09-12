### 0x00 
本着不折腾不会的信条，又开始整活路由器的相关内容。记得此前使用旧的笔记本电脑体验过 OpenWrt 的使用，这次直接在路由器上尝试。

路由器是小米 R4A 千兆版本。刷不死 breed 的忘记记录了.. 刷的固件包是 dalao 自编译的 OpenWrt [固件在这里](https://github.com/Cvjark/MyRouter/files/9542925/openwrt-ramips-mt7621-xiaomi_mi-router-4a-gigabit-squashfs-sysupgrade.zip)



### 0x01 相关命令
```C
uname -m  // 查看 CPU 架构

opkg print-architecture     // 查看可接受的架构
```

我的设备运行结果：

![image](https://user-images.githubusercontent.com/89090949/189539003-595cc3e5-ed17-4411-90fc-0d1f08a856af.png)

[package source](https://op.supes.top/packages/)


### 0x01 shadowsockets & 图形化界面
Github 上的库：

[shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)


