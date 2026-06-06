# 屏幕翻译工具 0.1.0

发布日期：2026-06-06

发布包：`screen-translator-0.1.0-win-x64.zip`

SHA256：`d9fae68eb946add23f409a9bcedd2aa9641af210519ef6aa3eed61dc60a27c00`

## 本次发布内容

`0.1.0` 是第一个公开发布的 Windows x64 便携版。

已包含功能：

- 框选屏幕区域进行翻译。
- 使用 Windows OCR 和 UI Automation 提取屏幕文字。
- 支持配置 OpenAI 兼容 API。
- 支持从兼容服务获取模型列表。
- 支持悬浮翻译结果窗口，并在需要时回退到结果面板。
- 支持对已选区域进行连续翻译。
- 支持托盘菜单控制和可配置的全局快捷键。
- 本地保存设置，并使用 Windows DPAPI 保护 API Key。

## 下载

下载并解压：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip
```

校验下载文件：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip.sha256
```

## 运行要求

- Windows 10 或 Windows 11 x64。
- 发布包为自包含版本，不需要额外安装 .NET。
- 一个 OpenAI 兼容的 API 地址、API Key 和可用模型。

## 运行方法

1. 解压发布包。
2. 运行 `ScreenTranslator.App.exe`。
3. 在应用内配置 Base URL、API Key 和模型。
4. 点击获取模型按钮，确认 API 连接并加载模型列表。
5. 通过主窗口、托盘菜单或快捷键开始屏幕区域翻译。

## 注意事项

- API Key 保存在本机，并按当前 Windows 用户进行加密保护。
- 不要只移动单独的 `.exe` 文件，解压后的文件夹内容需要保持在一起。
- 这是便携版压缩包，不是安装程序。
