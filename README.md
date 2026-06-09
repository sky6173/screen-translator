# 屏幕翻译

一个 Windows 桌面屏幕翻译工具。它可以框选屏幕区域，通过 Windows OCR 或 UI Automation 提取文字，再调用 OpenAI 兼容接口进行翻译，并把结果显示在轻量悬浮窗口或结果面板中。

## 下载最新版

当前正式版本：`v0.1.1`

[前往 v0.1.1 下载页面](https://github.com/sky6173/screen-translator/releases/tag/v0.1.1)

推荐普通用户下载发布页里的 Windows 安装包。便携版 zip 保留给不想安装、只想临时运行的场景。

## 运行要求

- Windows 10 或 Windows 11 x64。
- 一个 OpenAI 兼容的 API 地址、API Key 和可用模型。
- 发布包是自包含版本，不需要额外安装 .NET。

## 安装包使用方法

1. 下载并运行 `screen-translator-0.1.1-win-x64-setup.exe`。
2. 按中文安装向导完成安装，可以选择安装目录。
3. 从开始菜单或桌面快捷方式启动“屏幕翻译”。
4. 在应用内配置 Base URL、API Key 和模型。
5. 点击“获取模型”，用模型列表确认 API 连接是否可用。
6. 通过主窗口、托盘菜单或快捷键开始框选区域翻译。

## 便携版运行方法

1. 下载并解压 `screen-translator-0.1.1-win-x64.zip`。
2. 在解压后的文件夹中运行 `ScreenTranslator.App.exe`。
3. 不要只移动单独的 `.exe` 文件，解压后的文件夹内容需要保持在一起。

## 隐私和设置

- API Key 只保存在本机。
- 已保存的 API Key 会使用 Windows DPAPI 按当前 Windows 用户保护。
- 不要公开分享 `%APPDATA%\ScreenTranslator\settings.json`。
