<div align="center">

# Steam Wrapped

**Turn your Steam hours into a yearly wrapped.**
**把 Steam 上的上千小时，做成每年一份的年报。**

[中文](#中文) · [English](#english)

[**⬇ 下载最新版 / Download**](https://github.com/bendanxiaogou520/steam-wrapped/releases/latest/download/steam-wrapped.apk)

</div>

---

## 中文

### 这是什么

一个手机上的 Steam 游戏数据 App。不做社交、不推送、不抽卡，只做一件事：把你自己的游戏记录摊开给你看。

界面参考了小黑盒、Steam 官方 App 和 PS5，也补了它们没做好的地方。

### 能看什么

| 模块 | 内容 |
| --- | --- |
| 总览 | 总时长、游戏款数、成就数、最近在玩 |
| 年报 | 一整屏的年度总结：封面墙、Steam 官方年度时长、你的年度之最 |
| 游戏详情 | 时长、成就完成度、全球稀有度、游戏简介 |
| 年谱 | 按年份回看你玩过什么 |

### 怎么装

1. 点上面的 **下载最新版**（约 1.3 MB）
2. 手机提示「不允许安装未知应用」→ 这一次允许
3. 装完打开就能用

**系统要求**：Android 8.0 及以上。

### 数据从哪来

读你自己电脑上的 Steam 本地记录（`localconfig.vdf`），通过 adb 推到手机。全程不经过任何服务器，也没有账号体系。

### 版本

只保留最近三个版本，旧的直接删掉。

| 版本 | 日期 | 变化 |
| --- | --- | --- |
| **v0.7.2** | 2026-11-12 | 年报改用 Steam 官方真实年度时长（最新） |
| v0.7.0 | 2026-11-12 | 年报首屏重做：封面墙 |
| v0.6.2 | 2026-11-12 | 年报首屏重做 + 修「点不进去」 |

> 原名「玽游」，取自作者网名。仓库用了通用名方便检索；**App 内部名字没改，装完后手机图标上仍显示「玽游」**。

---

## English

### What it is

A Steam stats viewer for Android. It turns your own local playtime records into a yearly wrapped — a full-screen recap with a cover wall, your official annual hours, and your year's highlights.

The UI borrows from Xiaheihe, the official Steam app and PS5, and fixes a few things they get wrong.

### Features

| Screen | What you get |
| --- | --- |
| Overview | Total hours, game count, achievements, recently played |
| Wrapped | Full-screen yearly recap: cover wall, Steam's official annual hours, your year's bests |
| Game detail | Playtime, achievement completion, global rarity, store description |
| Timeline | Browse what you played, year by year |

### Install

1. Download the APK above (~1.3 MB)
2. Allow "install unknown apps" once when prompted
3. Open it — that's it

**Requires** Android 8.0 or newer.

### Where the data comes from

It reads `localconfig.vdf` from your own PC's Steam install and pushes it to the phone over adb. No server, no account, no telemetry — nothing leaves your devices.

### Versions

Only the latest three builds are kept here; older ones are removed on purpose.

| Version | Date | Notes |
| --- | --- | --- |
| **v0.7.2** | 2026-11-12 | Wrapped now uses Steam's official annual hours (latest) |
| v0.7.0 | 2026-11-12 | Wrapped first screen rebuilt: cover wall |
| v0.6.2 | 2026-11-12 | Wrapped rebuild + fixed unclickable card |

<sub>Formerly 玽游, named after the author's handle. Renamed so other people can use it without the personal name.</sub>
