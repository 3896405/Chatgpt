<!-- CURRENT_DOWNLOADS_BEGIN -->
# ChatGPT 安装版与完整便携版

最新版本：**26.1021.3705.0**。两种版本分别提供，历史发行版保留。

| 版本 | 适用情况 | 下载 |
| --- | --- | --- |
| 安装版 26.1021.3705.0 | 推荐 Windows 10 build 19041 及以上、Windows 11 的 x64 电脑 | [安装版下载](https://github.com/3896405/Chatgpt/releases/tag/installer-v26.1021.3705.0) |
| 完整便携版 26.1021.3705.0 | 第三方完整原包；启动检查未通过，按待验证测试版提供 | [完整便携版下载](https://github.com/3896405/Chatgpt/releases/tag/portable-v26.1021.3705.0) |

## 安装版使用

完整解压 ZIP，先运行“安装ChatGPT.cmd”，安装成功后运行“创建ChatGPT桌面快捷方式.cmd”。两个脚本独立，成功后窗口自动关闭。保留 ChatGPT.ico，桌面快捷方式使用此图标。

## 完整便携版使用

完整解压到较短路径，例如 D:\AI\Codex。首次运行 Setup Codex.cmd 按需完成初始化，日常运行 Codex.cmd。不要单独移动 EXE 或删除 _internal 中的文件。

便携包来自 [lusipad/unofficial-codex-app-offline 的同版本发行版](https://github.com/lusipad/unofficial-codex-app-offline/releases/tag/offline-v26.1021.3705.0)，原 ZIP 未修改，已核对源发布 SHA256。它不同于本仓库旧版自行简化的便携包，也不是 OpenAI 官方发行版。

已核对安装包完整性及便携 ZIP 的源发布 SHA256。便携程序的本机隔离启动检查未确认窗口及任务服务就绪，日志出现 Desktop startup policy read failed，故标为待验证测试版，建议优先使用安装版。登录后的任务、全部插件和旧 Windows 系统兼容性仍需实际验证。AI 功能需要网络及有效账号。

[全部历史版本](https://github.com/3896405/Chatgpt/releases)
<!-- CURRENT_DOWNLOADS_END -->

<details>
<summary>历史版本说明（保留）</summary>

# ChatGPT 安装版与便携版

## 同事推荐安装

**推荐 Windows 10 build 19041 及以上系统（含 Windows 11，x64）的同事使用安装版。**

[下载安装版 26.1021.3705.0](https://github.com/3896405/Chatgpt/releases/tag/installer-v26.1021.3705.0)

解压后先运行安装ChatGPT.cmd，完成后运行创建ChatGPT桌面快捷方式.cmd。低于 build 19041 的系统不能安装该 MSIX。

---

# ChatGPT Portable

Unofficial Windows x64 portable repack of ChatGPT/Codex 26.1007.9446.0.

## Download

[Download portable ZIP](https://github.com/3896405/Chatgpt/releases/download/portable-v26.1007.9446.0/ChatGPT-Portable-26.1007.9446.0.zip)

Extract the complete ZIP to a short path, for example D:\ChatGPT, then open **ChatGPT.exe**. No installation or launcher script is required. Keep all runtime files together.

AI services require a network connection and a valid account. The app uses the current Windows user's application configuration.

## Compatibility

The MSIX installer build-19041 check is not performed. This does not guarantee older Windows compatibility. Windows build 18363 has not been tested. Local direct-launch checks confirmed the app window and bundled task service started and survived 30 seconds; sign-in, actual tasks and all plugins have not been validated.

## Credits

Based on official OpenAI MSIX application files and portable patches from [lusipad/unofficial-codex-app-offline](https://github.com/lusipad/unofficial-codex-app-offline). This is a modified, unofficial distribution, not an OpenAI release. It does not bundle the third-party project's extra skill seed, Web Gateway or setup wizard. Two peripheral native modules are absent from the source payload.

SHA256: d922c98499a756259dde326e56a4ba0331dffa3d3dd44f9f41843d95f4c2f2f4

</details>
