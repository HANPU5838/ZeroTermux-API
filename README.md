# ZeroTermux:API · 正式版

> 配套组件正式版发布仓库。源码暂不在此维护，本仓库只提供可直接安装的 APK 与说明。

## 这是什么

`Termux:API` 是 [ZeroTermux 加固版](https://github.com/HANPU5838/ZeroTermux-hardened) 的配套组件，让终端可以调用手机系统能力：

- 剪贴板读写、通知、振动、电池信息
- 传感器、定位、Wi-Fi / 网络信息
- 短信、通讯录、摄像头、音频、亮度、音量等

**不装也能用**：主程序本身就是完整终端环境，本组件按需安装。

| 项 | 值 |
|---|---|
| 包名 | `com.termux.api` |
| 版本 | `0.53.0-zero.14` |
| 签名 | 与主程序、Termux:X11 一致，可互相覆盖升级，数据不丢 |
| 是否必装 | 否，按需 |

## 安装

1. 先装主程序：<https://github.com/HANPU5838/ZeroTermux-hardened/releases>
2. 下载本仓库 **Releases** 里最新版的 APK，安装即可

## 更新

主程序内会检测本仓库的最新 Release；也可以直接在 Releases 页面下载新版覆盖安装。

## 相关仓库

| 软件 | 仓库 | 说明 |
|---|---|---|
| 主程序 | [ZeroTermux-hardened](https://github.com/HANPU5838/ZeroTermux-hardened) | 必装 |
| 本组件 | **ZeroTermux-API** | 按需 |
| X11 显示 | [ZeroTermux-X11](https://github.com/HANPU5838/ZeroTermux-X11) | 按需 |

## 归属与许可

本 APK 为基于 Termux:API / 上游 ZeroTermux 生态的第三方配套构建，**不是官方发布**。
上游原作者与完整的第三方衍生构建声明见主仓库 README；许可证遵循上游 GPLv3 only，不改变项目归属。

## 维护者

- 网站：<https://hanpuhan.cn>
- 邮箱：<640615397@qq.com>
- QQ 群及个人 QQ：见主仓库 README
