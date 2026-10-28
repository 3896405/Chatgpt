<!-- CURRENT_DOWNLOADS_BEGIN -->
# ChatGPT 安装版与便携版

最新版本：**26.1023.6123.0**。历史发行版保留。

| 版本 | 使用方式 | 下载 |
| --- | --- | --- |
| 安装版 26.1023.6123.0 | 推荐 Windows 10 build 19041 及以上、Windows 11 x64；一个 CMD 自动安装并创建桌面快捷方式 | [安装版下载](https://github.com/3896405/Chatgpt/releases/tag/installer-v26.1023.6123.0) |
| 纯程序目录便携版 26.1023.6123.0 | 完整解压后直接双击根目录 ChatGPT.exe，无需启动脚本 | [便携版下载](https://github.com/3896405/Chatgpt/releases/tag/portable-flat-v26.1023.6123.0) |

## 安装版使用

完整解压 ZIP，双击唯一的 **安装ChatGPT.cmd**，按提示允许管理员权限。安装段沿用默认脚本，成功后自动创建桌面快捷方式，再显示“平台数据分析部”完成窗口，可选择打开应用或完成退出。失败时停留显示错误，不会显示安装成功。

升级前先保存工作并完全退出应用；不要切换到其他 Windows 账号安装。图标保存到用户本地应用数据目录，删除解压目录不影响快捷方式图标。

## 便携版使用

完整解压到固定目录，直接双击根目录的 **ChatGPT.exe**。保留 resources、locales 等全部配套文件，不要只复制 EXE。

本版直接提取自官方 MSIX 的 app 目录，未修改程序、未添加第三方补丁、初始化向导、外层启动器或额外技能。不需要运行 CMD、PowerShell、Setup，没有 _internal 套目录。

便携版已通过本机隔离配置的 30 秒窗口及包内后端启动检查；测试机器已有运行时缓存。安装版通过默认安装段一致性、隔离快捷方式与完成窗口测试，未在本机实际执行升级。全新系统、全部插件和任务、旧 Windows 兼容性仍需实测。AI 功能需联网及有效账号，配置可能保存在当前 Windows 用户目录。

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
