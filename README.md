# GHOST RUN

**赛博朋克城市跑酷 · 黑客松可玩 Demo**

穿行于霓虹城市，在换道、转弯、跳跃和滑铲之间收集记忆碎片，维持角色稳定度。项目使用 Unreal Engine，结合全息粒子角色、动态环境效果和可选 AI 视觉策略调度。

## 下载与运行

**[下载 Windows Demo（ZIP，约 1.90 GiB）](https://github.com/ningbo00/ghostRun/releases/download/v0.1.0-hackathon/GhostRun_Demo_Win64_20260924_100604.zip)** · [版本页面与 SHA256 校验文件](https://github.com/ningbo00/ghostRun/releases/latest)

1. 下载上面的 Demo ZIP，完整解压。
2. 打开解压目录中的 `Windows` 文件夹。
3. 双击 `Start_Game.cmd`，进入开始界面后开始游玩。

无需安装 Unreal 编辑器、Python 或配置 API 密钥即可体验普通模式。请不要在压缩包内直接运行，也不要单独移动 EXE。GitHub 自动生成的 **Source code** 压缩包仅包含本展示页，不包含游戏。

## 体验亮点

- 立体城市跑酷：换道、急转、断桥跳跃与滑铲。
- 全息粒子角色、霓虹城市、Lumen 光照与动态环境效果。
- 收集过去、现在、未来的记忆碎片，查看本局身份报告。
- 可选 AI 环境调度：默认本地模拟，也支持通过随包网关连接模型服务。
- F11 实时效果面板，可用于现场讲解光照、雾和后处理。

## 操作

| 按键 | 功能 |
| --- | --- |
| A / D 或 ← / → | 换道、转弯 |
| 空格 / W / ↑ | 跳跃 |
| S / ↓ / 左 Ctrl | 滑铲 |
| Shift | 主动减速 |
| E | 扫描前方 T 字路口路牌 |
| P / R | 暂停 / 重新开始 |
| F11 | 效果调试 |
| Alt + Enter | 切换全屏 |

完整玩法、叙事调试和可选 AI 模式说明见 [运行指南](PLAY_GUIDE.txt)。

## 运行环境

- 64 位 Windows，支持 DirectX 12 / Shader Model 6 的显卡及较新驱动。
- Lumen、光线追踪和粒子效果对显卡要求较高；可在 F11 面板降低内部渲染比例和画质。
- 首次启动可能较慢。如提示缺少运行库，请安装包内 `Windows/Engine/Extras/Redist/en-us/vc_redist.x64.exe`。
- 可选 HTTP 模拟 / 在线模型模式需要 Python 3.10+；在线模型另需自己的 API 配置和网络连接。普通游玩不需要这些配置。

## 实机截图

以下为本次构建的自动测试截图，展示 F11 效果调试模式；Development 构建可能显示引擎调试提示。

![GhostRun 实机效果调试画面](images/gameplay-debug.png)

## 版本说明

当前为 Windows x64 Development 展示构建，保留调试功能。构建时间：2026-09-24；发布标签：`v0.1.0-hackathon`。仓库用于项目介绍与 Demo 分发，完整 UE 工程不包含在此仓库中。

该 ZIP 的 SHA256：

```text
ABE19D596807DABBD53E8EF559D6A14E90090313977D992E6D41AB9453F90F38
```
