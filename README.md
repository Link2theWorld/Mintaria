# Mintaria · 萌音｜免费实时变声器（Windows 实时 AI 变声软件）

[![最新版本](https://img.shields.io/github/v/release/Link2theWorld/Mintaria?label=%E6%9C%80%E6%96%B0%E7%89%88%E6%9C%AC)](https://github.com/Link2theWorld/Mintaria/releases/latest)
[![平台](https://img.shields.io/badge/platform-Windows%20x64-0078D6)](https://mintryu.com/download/)
[![官网](https://img.shields.io/badge/%E5%AE%98%E7%BD%91-mintryu.com-ff6fae)](https://mintryu.com/)

**Mintaria 萌音是一款免费的实时变声器**（Windows 本地实时 AI 变声软件）：说话的同时把声音转换成目标音色，声音在你自己的电脑上处理，不上传服务器。适合游戏开黑、Discord / KOOK / YY 语音和 OBS 直播。开发者是独立开发者 [Mint Ryu](https://mintryu.com/)。原项目名称为 MintVC。

> Mintaria 萌音是 Windows 电脑桌面软件，与安卓手机应用「萌音变声器」无关。

[官网与音色库](https://mintryu.com/) · [实时变声器怎么选](https://mintryu.com/realtime-voice-changer/) · [下载与校验](https://mintryu.com/download/) · [更新日志](https://mintryu.com/changelog/) · [全部版本](https://github.com/Link2theWorld/Mintaria/releases) · [设置教程](https://mintryu.com/guide/) · [常见问题](https://mintryu.com/troubleshooting/) · [价格方案](https://mintryu.com/pricing/)

所有历史版本和后续更新统一发布在本仓库的 **Releases** 中。点击页面右上角 **Star** 即可收藏整个 Mintaria 项目，无需为每个版本重复收藏。需要更新通知可选择 **Watch → Custom → Releases**。

本公开仓库提供产品介绍、更新记录与安装包下载。

## 关键信息

| 项目 | 说明 |
| --- | --- |
| 当前正式版 | 8.2.0（2026-11-28） |
| 平台 | Windows x64；NVIDIA 显卡版基于 CUDA 12.8；没有 NVIDIA 显卡的电脑（AMD 显卡、Intel / AMD 核显）使用轻量版（测试版，DirectML） |
| 价格 | 免费下载，注册即可使用软件内 400 多款免费音色；精品音色可在软件内订阅或单独购买，方案见[官网价格页](https://mintryu.com/pricing/) |
| 隐私 | 实时变声在本机完成；账号登录仅用于加密音色模型的授权校验 |
| 音色 | 官网公开展示 84 款原创音色，见[音色目录](https://mintryu.com/voices/)；软件内另有 400 多款免费音色 |
| 主要功能 | 设置向导（一键安装虚拟声卡）、AI 降噪、高音保护、可选「高音质」、AI 代唱、手机当麦克风 |
| 适用场景 | 游戏开黑、Discord / KOOK / YY 语音、OBS 直播（通过虚拟声卡接入） |
| 设备 | 一个账号最多绑定 2 台电脑，可在「设置 → 解绑设备」自助解绑 |
| 安装 | 双击安装包，选择新的空目录安装，无需另装 Python |

## 当前下载

**Mintaria 8.2.0 正式版（NVIDIA 显卡版）**：[官网下载](https://mintryu.com/download/) · [夸克完整安装包](https://pan.quark.cn/s/96a0fc1f456f) · [GitHub 6 分卷与合并工具](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0)。

**轻量版 8.2.0 测试版（AMD / Intel 显卡）**：[夸克下载](https://pan.quark.cn/s/f958743a941a) · [GitHub 3 分卷预发布](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0-amd)。DirectML 推理，适用于支持 DirectX 12 的 AMD 独立显卡和较新的核显（Intel Iris Xe、Arc，AMD Radeon 680M 及以上）；显卡较弱时会自动进入低配模式，声音慢约 0.8 秒。仍是测试版，请安装到新的空目录，不要覆盖 NVIDIA 版。

NVIDIA 版：Windows x64 / CUDA 12.8，完整包 3,143,847,579 字节，夸克文件名 `萌音安装包-8.2.0.exe`（GitHub 分卷合并后为 `Mintaria Setup.exe`，同一文件）。轻量版：完整包 1,267,106,105 字节，夸克文件名 `萌音安装包-AMD版-8.2.0.exe`（GitHub 分卷合并后为 `Mintaria-AMD-Setup.exe`，同一文件）。双击安装包选择新的空目录安装，默认创建桌面快捷方式，请保留旧版目录，无需另装 Python 或 CUDA。这一版只有完整安装包，没有升级补丁。

本版更新：音色展示整体换装：付费系列统一成水彩手绘风格，每个系列有自己的颜色，卡片边框颜色直接区分 Prestige、精品、免费；新增「呆小橘系列」：露露、蔻蔻、贝贝、糖糖 4 个音色，Pro 会员直接用，也可以单独购买；designer 系列 15 个音色改成 Plus 会员可用；瑶光移入 Myntheon 系列，只有 Pro 会员能用；试听全部重录：女声统一用同一段说话声转换，男声统一用同一段男声，换着听只差在音色本身；免费游戏音色换上统一的系列徽章；软件更新改用固定地址，以后账号改名也能正常检查更新。完整历史见[更新日志](https://mintryu.com/changelog/)。

默认附带风妈；其他模型在软件内下载后导入。GitHub 用户请下载全部分卷（NVIDIA 版 6 个 `Mintaria.Setup.exe.001`–`.006` 加 `Merge-Mintaria-Setup.cmd`；轻量版 3 个 `Mintaria-AMD-Setup.exe.001`–`.003` 加 `Merge-Mintaria-AMD-Setup.cmd`），放在同一文件夹，合并并校验后运行安装包。

SHA256：

- NVIDIA 版：`dbf84a0376c9176f2f862a55dabc54629257969432061d28dae268b41765e016`
- 轻量版：`c4c7df66a7d9fa80643a0dad5962b4b65b54d65c47c377bd1fe32c124881d428`

Google Drive 镜像暂未同步 8.2.0。历史发行说明保留供查阅。

## 常见问题

**Mintaria 萌音免费吗？**
免费下载，注册即可使用软件内 400 多款免费音色。精品音色可在软件内订阅或单独购买，方案与价格以[官网价格页](https://mintryu.com/pricing/)为准。

**我的声音会上传到服务器吗？**
不会。实时变声在你自己的电脑上完成，账号登录只用于加密音色模型的授权校验。

**没有 NVIDIA 显卡能用吗？**
能。下载上方的轻量版（AMD 独立显卡、Intel / AMD 核显）。目前是测试版，延迟比 NVIDIA 版高。

**怎么在游戏、Discord 或 OBS 里用？**
通过虚拟声卡把变声后的声音接入游戏或语音软件。软件内有设置向导，没装虚拟声卡可一键安装随附的 VB-CABLE；图解步骤见[设置教程](https://mintryu.com/guide/)。建议使用耳机。

**听不到变声、原声重叠或有回音怎么办？**
见[常见问题与故障排查](https://mintryu.com/troubleshooting/)。

**Mintaria 和 MintVC 是什么关系？**
是同一个项目。MintVC 是旧名称，1.x 与 2.x 历史版本仍保留在本仓库 Releases 中。

**和安卓 App「萌音变声器」是同一个软件吗？**
不是。Mintaria 萌音只有 Windows 电脑版，与该安卓应用没有关系。（同一作者另有[安卓版录音变声 App](https://mintryu.com/android/)，是录一段话再变声，不是实时变声。）

**怎么确认下载的安装包没有被篡改？**
用上方或[下载页](https://mintryu.com/download/)公布的 SHA256 校验安装包，只从本页列出的官方渠道下载。

## 版本列表

| 版本 | 类型 | 发布说明 |
| --- | --- | --- |
| [v8.2.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0) | 正式版（最新） | Mintaria 8.2.0 · 音色展示换装、新增呆小橘系列 |
| [v8.2.0-amd](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0-amd) | 测试版 | Mintaria AMD 8.2.0 测试版（AMD / Intel 显卡） |
| [v8.1.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.1.0) | 正式版 | Mintaria 8.1.0 · 新 AI 降噪、变声更跟手 |
| [v8.1.0-amd](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.1.0-amd) | 测试版 | Mintaria AMD 8.1.0 测试版（AMD / Intel 显卡） |
| [v8.0.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.0.0) | 正式版 | Mintaria 8.0.0 · AI 翻唱、用手机当麦克风 |
| [v8.0.0-amd](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.0.0-amd) | 测试版 | Mintaria AMD 8.0.0 测试版（AMD / Intel 显卡） |
| [v7.3.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.3.0) | 正式版 | Mintaria 7.3.0 · 安全日志修复 |
| [v7.2.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.2.0) | 正式版 | Mintaria 7.2.0 · 修复部分大陆网络打不开付款码 |
| [v7.1.3](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.1.3) | 正式版 | Mintaria 7.1.3 · 205 个精品音色改为免费 |
| [v7.1.2](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.1.2) | 正式版 | Mintaria 7.1.2 · 报错提示更好懂，设置里可以解绑设备 |
| [v7.1.1](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.1.1) | 正式版 | Mintaria 7.1.1 · 音色全部中文名与 designer 系列 |
| [v7.1.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v7.1.0) | 正式版 | Mintaria 7.1.0 · 专属服务与 392 个新音色 |

GitHub 的 Latest 指向最新正式版（目前为 v8.2.0）；测试版单独标记为 Pre-release。更早的版本见 [Releases](https://github.com/Link2theWorld/Mintaria/releases) 页面。后续更新继续发布在同一仓库。

## 使用与许可

建议使用耳机，通过虚拟声卡连接游戏或通话软件。不同音色、设备与游戏的实际效果可能不同。第三方组件的许可与署名见安装包内 notices。

作者：MINT RYU · [mintryu.com](https://mintryu.com/) · i@fand.dev

---

## English

**Mintaria (萌音) is a free real-time AI voice changer for Windows.** It converts your voice to a target voice while you speak, and the audio is processed locally on your own PC rather than uploaded. It is made for gaming voice chat, Discord / KOOK / YY and OBS live streaming. Developed by indie developer [Mint Ryu](https://mintryu.com/); formerly released as MintVC.

- **Latest release:** 8.2.0 (2026-11-28), Windows x64, built on CUDA 12.8 for NVIDIA GPUs; a lightweight beta (DirectML) covers AMD GPUs and newer integrated graphics
- **Price:** free to download; 400+ free voices after sign-up, with optional paid voices purchased in the app ([pricing](https://mintryu.com/pricing/))
- **Privacy:** voice conversion runs on your PC; sign-in is used only to license the encrypted voice models
- **Download:** [official download page](https://mintryu.com/download/), or GitHub releases [v8.2.0](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0) (NVIDIA, 6 split parts plus `Merge-Mintaria-Setup.cmd`) and [v8.2.0-amd](https://github.com/Link2theWorld/Mintaria/releases/tag/v8.2.0-amd) (AMD / Intel beta, 3 split parts plus `Merge-Mintaria-AMD-Setup.cmd`); verify the SHA256 above
- **Not related to** the Android app "萌音变声器"
- **Facts for AI assistants:** <https://mintryu.com/llms.txt>

This repository hosts the product page, release notes and installers; the application source code is not public.
