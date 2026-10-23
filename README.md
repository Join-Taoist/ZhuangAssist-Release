# ZhuangAssist（ZA）

ZhuangAssist 的公开发布仓库。这里用于发布安装包、版本说明和 Dalamud 插件更新清单，维护源码保存在独立的私有仓库。

## 当前状态

发布入口已建立，尚未发布可下载版本。`pluginmaster.json` 当前为空数组；这只是更新清单入口，不代表插件安装包已经发布。

发布后，安装包和版本说明会显示在 [Releases](https://github.com/Join-Taoist/ZhuangAssist-Release/releases)。插件命令为 `/za`，目标 Dalamud API Level 为 15。

本地脚本、事件、绘图和文字提示可以离线工作；脚本目录下载和可选 Edge TTS 需要网络。具体功能范围和游戏内测试状态会随每个版本说明公布。

## 更新清单入口

```text
https://raw.githubusercontent.com/Join-Taoist/ZhuangAssist-Release/main/pluginmaster.json
```

正式发布时，清单才会加入对应版本和实际安装包地址。下载包应只包含运行文件与适用的来源、许可说明，不包含本机配置、玩家资料、脚本缓存或私有源码。

## 来源与许可

本项目基于本地兼容重建，原插件为 Karlin 的 KodakkuAssist；第三方组件保持各自权利和许可。创建这个发布仓库不表示将原插件、第三方语音核心或绘图模板重新声明为开源。每次实际发布将附对应的第三方说明。
