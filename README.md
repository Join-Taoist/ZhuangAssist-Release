# ZhuangAssist（ZA）

作者：**Join-Taoist**。此公开仓库只提供混淆后的正式安装包、插件更新清单和说明；维护源码保存在独立私有仓库。

当前正式版 **0.8.0**，命令 `/za`，Dalamud API Level **15**。完整功能、验证分类和限制见 [版本说明](releases/0.8.0.md)。

## 卫月仓库地址

```text
https://raw.githubusercontent.com/Join-Taoist/ZhuangAssist-Release/main/pluginmaster.json
```

添加至卫月“自定义插件仓库”，刷新后搜索 ZhuangAssist。已有同名开发插件时避免同时启用两个实例。更新会沿用已有 ZA 独立配置。

运行 `/za`，在“脚本地址”添加原版格式的 JSON 地址，再到“可用脚本”选择、下载和管理脚本。脚本以外部 C# 文件保存；新安装不附带第三方战斗脚本或个人配置。

可用脚本将当前地图的“未安装 → 可更新 → 已安装”排在前面。打开列表可后台检查目录更新，亦可手动检查；更新脚本仍需点击更新按钮。此自动检查可以关闭。

本地脚本编译、事件、绘图和本地提示不依赖账号验证或在线心跳。脚本目录下载和可选 Edge TTS 需要网络；在线语音默认关闭，首次合成会把待朗读文字交给微软语音服务。普通本地语音及游戏 echo 的 SE 提示音保留。

正式 ZIP 与校验文件见 [Releases](https://github.com/Join-Taoist/ZhuangAssist-Release/releases)。自 0.8.0 起，公开安装包中的 ZA 主程序集和语音核心均经过混淆，保留脚本 API 和配置格式。包内不含源码、调试符号、混淆映射、SDK、原版插件 DLL 或私人资料。ZIP 校验见 SHA256SUMS.txt，包内逐文件校验见 SHA256.json。

## 来源

原版 KodakkuAssist 作者为 Karlin；现有脚本及第三方组件保持各自的作者、权利和许可。见 [第三方说明](THIRD-PARTY-NOTICES.md) 及包内 licenses。没有给原插件、第三方语音核心或绘图模板重新声明统一开源许可。
