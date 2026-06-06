# 屏幕翻译工具

一个 Windows 桌面屏幕翻译应用。

它可以让你框选屏幕区域，通过 Windows OCR 或 UI Automation 提取文字，再调用 OpenAI 兼容接口进行翻译，并把结果显示在轻量悬浮窗口或结果面板中。

## 最新版本

版本：`0.1.0`

下载文件：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip
```

校验文件：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip.sha256
```

版本说明：

```text
releases/v0.1.0/RELEASE_NOTES.md
```

## 运行要求

- Windows 10 或 Windows 11 x64。
- 一个 OpenAI 兼容的 API 地址、API Key 和可用模型。
- 发布包为自包含版本，不需要额外安装 .NET。

## 使用方法

1. 解压 `screen-translator-0.1.0-win-x64.zip`。
2. 在解压后的文件夹中运行 `ScreenTranslator.App.exe`。
3. 在应用内配置 Base URL、API Key 和模型。
4. 点击获取模型按钮，用模型列表确认 API 连接是否可用。
5. 通过主窗口、托盘菜单或快捷键开始框选区域翻译。

## 隐私和设置

- API Key 只保存在本机。
- 已保存的 API Key 会使用 Windows DPAPI 按当前 Windows 用户保护。
- 不要公开分享 `%APPDATA%\ScreenTranslator\settings.json`。

## 源代码

源代码、开发文档和内部实现记录保存在私有开发仓库中。这个公开仓库只存放面向用户的发布说明和正式发布包。
