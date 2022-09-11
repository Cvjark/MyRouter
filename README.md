### 0x00 
本着不折腾不会的信条，又开始整活路由器的相关内容。记得此前使用旧的笔记本电脑体验过 OpenWrt 的使用，这次直接在路由器上尝试。

路由器是小米 R4A 千兆版本。刷不死 breed 的忘记记录了.. 刷的固件包是 dalao 自编译的 OpenWrt [固件在这里](https://github.com/Cvjark/MyRouter/files/9542925/openwrt-ramips-mt7621-xiaomi_mi-router-4a-gigabit-squashfs-sysupgrade.zip)

https://pub-api-1.bianyuan.xyz/sub?target=ss&url=vmess%3A%2F%2FeyJob3N0IjoiIiwicGF0aCI6IiIsInRscyI6IiIsInZlcmlmeV9jZXJ0Ijp0cnVlLCJhZGQiOiIyMy5kb3VsdW9zLmljdSIsInBvcnQiOjI2MTIzLCJhaWQiOjIsIm5ldCI6InRjcCIsImhlYWRlclR5cGUiOiJub25lIiwidiI6IjIiLCJ0eXBlIjoidm1lc3MiLCJwcyI6InZpcDIt6aaZ5rivMSDljp%2FnlJ9JUCB8fOmZkOmAnzUwME0iLCJyZW1hcmsiOiJ2aXAyLemmmea4rzEg5Y6f55SfSVAgfHzpmZDpgJ81MDBNIiwiaWQiOiJiZmE3YTkxZC03ZjY3LTNkMzktODYxYy0zYTc1YjdlYzcwNjAiLCJjbGFzcyI6Mn0%3D&insert=false&emoji=true&list=false&tfo=false&scv=false&fdn=false&sort=false

### 0x01 相关命令
```C
uname -m  // 查看 CPU 架构

opkg print-architecture     // 查看可接受的架构
```

我的设备运行结果：

![image](https://user-images.githubusercontent.com/89090949/189539003-595cc3e5-ed17-4411-90fc-0d1f08a856af.png)



### 0x01 shadowsockets & 图形化界面
Github 上的库：

[shadowsocks-libev](https://github.com/shadowsocks/shadowsocks-libev)


