[![Lede](https://img.shields.io/badge/source-Lede-deeppink.svg?style=flat&logo=appveyor)](https://github.com/coolsnowwolf/lede)
[![openwrt](https://img.shields.io/badge/source-openwrt-tomato.svg?style=flat&logo=appveyor)](https://github.com/openwrt/openwrt)
[![lienol](https://img.shields.io/badge/source-Lienol-yellow.svg?style=flat&logo=appveyor)](https://github.com/Lienol/openwrt)
[![Mortal](https://img.shields.io/badge/source-Mortal-green.svg?style=flat&logo=appveyor)](https://github.com/immortalwrt/immortalwrt)


### 介绍

---

使用Lede或Openwrt源码在线编译x86固件！

<br />



### 固件编译

---

- [添加secrets](https://github.com/libntdll/common/blob/main/doc/secrets.md )

| Secrets名称        | 功能                        | 备注 |
| ------------------ | --------------------------- | ---- |
| REPO_TOKEN         | Gtihub actions 编译用 token | 必须 |
| TELEGRAM_CHAT_ID   | Telegram 通知个人 ID        | 可选 |
| TELEGRAM_BOT_TOKEN | Telegram 通知 token         | 可选 |
| PUSH_PLUS_TOKEN    | Pushplus 微信通知 token     | 可选 |



- [开启缓存加速](https://github.com/libntdll/common/blob/main/doc/ccache.md)



- [基本uci命令](https://github.com/libntdll/common/blob/main/doc/UCI.md)



- [基本lxc操作命令](https://github.com/libntdll/common/blob/main/doc/pct.md)

<br />



### 固件安装、更新

---


  - PVE lxc容器Openwrt


    - 《[lxc容器OpenWrt一键安装、更新](https://github.com/libntdll/pve)》

  - 普通OpenWrt


    - 命令行输入`autoupdate`更新，详见其命令行说明；或使用`luci-app-autoupdate`插件更新(编译默认安装)

​    <br />
