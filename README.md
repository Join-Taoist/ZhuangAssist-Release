# ZhuangAssist（ZA）

ZhuangAssist 的公开发布仓库。这里用于发布安装包、版本说明和 Dalamud 插件更新清单，维护源码保存在独立的私有仓库。

## 当前状态

首个公开包版本为 **0.6.0**，插件命令为 `/za`，目标 Dalamud API Level 为 **15**。功能、验证分类与限制见 [0.6.0 版本说明](releases/0.6.0.md)。

安装包与校验文件位于 [Releases](https://github.com/Join-Taoist/ZhuangAssist-Release/releases)。源码不随运行包发布。

本地脚本、事件、绘图和文字提示可以离线工作；脚本目录下载和可选 Edge TTS 需要网络。具体功能范围和游戏内测试状态会随每个版本说明公布。

## 更新清单入口

```text
https://raw.githubusercontent.com/Join-Taoist/ZhuangAssist-Release/main/pluginmaster.json
```

在卫月设置的“自定义插件仓库”添加上述地址并启用，保存后刷新插件列表，搜索 **ZhuangAssist** 并安装。若已经启用同名开发插件，先停用开发插件，避免同名实例或命令冲突。

安装后输入 `/za`，在“脚本地址”添加原版格式的 JSON 目录地址，再到“脚本目录”下载并加载所需脚本。新安装不捆绑任何第三方脚本或个人配置；独立配置目录为 `%APPDATA%/XIVLauncherCN/pluginConfigs/ZhuangAssist/`。已有 ZA 配置继续沿用。

Edge TTS 在“设置 → 常规”中按需开启，首次合成需要网络；默认关闭。Windows 本地语音保留。安装包包含运行所需依赖及第三方说明，不包含本机配置、玩家资料、脚本缓存、调试符号或私有源码。

## 来源与许可

本项目基于本地兼容重建，原插件为 Karlin 的 KodakkuAssist；第三方组件保持各自权利和许可。原插件、第三方语音核心或绘图模板没有被重新声明为开源。组件来源与适用许可见 [第三方说明](THIRD-PARTY-NOTICES.md) 及安装包内的 licenses 目录。
