# 来源与第三方说明（公开运行包）

ZhuangAssist 是对 KodakkuAssist 0.6.0.1 的本地兼容重建，原作者为 Karlin。原 DLL 的 SHA-256 为 EBB4657BCDDD7CD51493C502E08521C19AFD6425EA939C001E510BF16E438325。原插件与验证库不作为运行依赖随包发布；本工程没有为原插件或全部重建代码追加统一开源许可。

运行包包含下列组件，其权利与许可保持原样：

- Microsoft.CodeAnalysis / Microsoft.CodeAnalysis.CSharp 4.10：Microsoft Roslyn，.NET Foundation 及贡献者，MIT。许可见 licenses/Roslyn-LICENSE.txt；来源 https://github.com/dotnet/roslyn 。
- System.Speech 8：.NET Foundation 及贡献者，MIT。许可见 licenses/System.Speech-LICENSE.txt；来源 https://github.com/dotnet/runtime/tree/v8.0.0/src/libraries/System.Speech 。
- NuGet.Versioning 6.11.1.2：.NET Foundation 及贡献者，Apache-2.0。见 licenses/NuGet.Client-LICENSE.txt 与 licenses/Apache-2.0.txt；来源 https://github.com/NuGet/NuGet.Client 。
- NAudio 2.2.1：Mark Heath 与贡献者，MIT。见 licenses/NAudio-LICENSE.txt；来源 https://github.com/naudio/NAudio 。
- System.Net.WebSockets.Client.Managed 1.0.22：Pingman Tools，MIT。见 licenses/ManagedWebSocket-LICENSE.txt；来源 https://github.com/PingmanTools/System.Net.WebSockets.Client.Managed 。
- ZhuangAssist.EdgeTTS：基于 AtmoOmen/EdgeTTS 提交 74cdac5c3021c20d5e102329aaccc36f910bf41c 编译，程序集改名以避免冲突。上游称主要逻辑来源于 ACT.FoxTTS；来源 https://github.com/AtmoOmen/EdgeTTS 。该核心库在上述提交没有独立许可文件；没有把另一仓库 EdgeTTS.Dalamud 的 MIT 许可解释为覆盖此核心库，也没有将其重新声明为 MIT。音色元数据来自同一上游。
- 嵌入的七个 Vfx 模板：tmp_circle、tmp_fan、tmp_donut、tmp_rect、tmp_rect2、TestLine2、Displacement，取自上述原插件的本地绘图资源。原作者及游戏素材的权利不因提取或本次发布而改变，未发现可为这些模板另行赋予的开源许可。

Dalamud、FFXIVClientStructs、Lumina、Lumina.Excel、Newtonsoft.Json、ImGui bindings 与 InteropGenerator.Runtime 由宿主提供，未将完整 SDK 捆绑在运行包中。原插件 DLL、NekoVerifierLib、旧 EdgeTTS.dll、第三方脚本样本、个人配置与私有源码均未随包发布。

附带的许可文本分别适用于其列出的组件，不推定为未声明组件或原插件的授权。
