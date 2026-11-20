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
| 碑林 | 满成就 / 稀有成就（<5%）/ 最近解锁（可展开全部） |
| 年谱 | 按年份回看你玩过什么 |

### 怎么装

1. 点上面的 **下载最新版**（约 2.4 MB）
2. 手机提示「不允许安装未知应用」→ 这一次允许
3. 装完打开就能用

**系统要求**：Android 8.0 及以上。

### 数据从哪来

读你自己电脑上的 Steam 本地记录（`localconfig.vdf` 和成就缓存），通过 adb 推到手机。全程不经过任何服务器，也没有账号体系 —— 不登录 Steam、不上传任何游戏数据。

### 版本

只保留最近三个版本，旧的直接删掉。

| 版本 | 日期 | 变化 |
| --- | --- | --- |
| **v1.1.7** | 2026-11-20 | 修成就图标加载慢：图床顺序反了，每条先吃一次 404（最新） |
| v1.1.6 | 2026-11-18 | 修新游戏成就没图标：完整 URL 也要能换图床兜底 |
| v1.1.4 | 2026-11-17 | 碑林重做：最近解锁 30 条 + 展开全部；修刷新后碑林不重画 |

> **v0.7.2 → v1.1.7 之间发生了什么**：接入 Xbox / Game Pass 游戏（靠启动器自己计时，因为微软不记这两款的时长）、加「碑林」成就展馆、修稀有度全 0%、把同步脚本并成一个 bat。版本号从 0.7 跳到 1.1 就是因为这几块是新功能，不只是修 bug。

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
| Hall of fame | Perfect games, rare achievements (<5%), latest unlocks with expand-all |
| Timeline | Browse what you played, year by year |

### Install

1. Download the APK above (~2.4 MB)
2. Allow "install unknown apps" once when prompted
3. Open it — that's it

**Requires** Android 8.0 or newer.

### Where the data comes from

It reads `localconfig.vdf` and your achievement cache from your own PC's Steam install, then pushes them to the phone over adb. No server, no account, no telemetry — nothing leaves your devices.

### Versions

Only the latest three builds are kept here; older ones are removed on purpose.

| Version | Date | Notes |
| --- | --- | --- |
| **v1.1.7** | 2026-11-20 | Fixed slow achievement icons: CDN order was reversed, every icon ate a 404 first (latest) |
| v1.1.6 | 2026-11-18 | Fixed missing icons on newer games: full URLs now get a CDN fallback too |
| v1.1.4 | 2026-11-17 | Hall of fame rebuilt: 30 recent unlocks + expand all |

> **What happened between v0.7.2 and v1.1.7**: Xbox / Game Pass support (timed by the launcher, since Microsoft records no playtime for those titles), a full achievement hall, a global-rarity fix, and one merged sync script. The jump from 0.7 to 1.1 marks new features rather than bug fixes.

<sub>Formerly 玽游, named after the author's handle. Renamed so other people can use it without the personal name.</sub>
