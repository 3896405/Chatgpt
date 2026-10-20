# ChatGPT 安装版与便携版

## 同事推荐安装

**推荐 Windows 10 build 19041 及以上系统（含 Windows 11，x64）的同事使用安装版。**

[下载安装版 26.1013.4894.0](https://github.com/3896405/Chatgpt/releases/tag/installer-v26.1013.4894.0)

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