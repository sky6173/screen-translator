# 屏幕翻译工具 0.1.0

发布日期：2026-06-06
安装程序补充发布：2026-06-07

推荐发布包：`screen-translator-0.1.0-win-x64-setup.exe`

安装程序 SHA256：`110ec03bf29173c55b93035edac0899ceea010d7ffb99d38d82c23e50598878a`

便携版发布包：`screen-translator-0.1.0-win-x64.zip`

便携版 SHA256：`d9fae68eb946add23f409a9bcedd2aa9641af210519ef6aa3eed61dc60a27c00`

## 本次发布内容

`0.1.0` 是第一个公开发布的 Windows x64 版本。

2026-06-07 补充了中文安装程序。新版安装程序使用现代化安装向导，支持选择安装目录，默认按当前 Windows 用户安装，并可通过 Windows 已安装应用/设置卸载。用户手动测试确认：安装向导正常、安装成功、卸载成功，并且卸载会移除安装程序创建的文件和文件夹。

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

推荐下载并运行安装程序：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64-setup.exe
```

校验安装程序：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64-setup.exe.sha256
```

也可以下载便携版压缩包：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip
```

校验便携版：

```text
releases/v0.1.0/screen-translator-0.1.0-win-x64.zip.sha256
```

## 运行要求

- Windows 10 或 Windows 11 x64。
- 发布包为自包含版本，不需要额外安装 .NET。
- 一个 OpenAI 兼容的 API 地址、API Key 和可用模型。

## 安装程序使用方法

1. 运行 `screen-translator-0.1.0-win-x64-setup.exe`。
2. 按中文安装向导完成安装。
3. 从开始菜单或桌面快捷方式启动 `屏幕翻译工具`。
4. 在应用内配置 Base URL、API Key 和模型。
5. 点击获取模型按钮，确认 API 连接并加载模型列表。
6. 通过主窗口、托盘菜单或快捷键开始屏幕区域翻译。
7. 如需卸载，可在 Windows 已安装应用/设置中卸载。

## 便携版运行方法

1. 解压发布包。
2. 运行 `ScreenTranslator.App.exe`。
3. 在应用内配置 Base URL、API Key 和模型。
4. 点击获取模型按钮，确认 API 连接并加载模型列表。
5. 通过主窗口、托盘菜单或快捷键开始屏幕区域翻译。

## 注意事项

- API Key 保存在本机，并按当前 Windows 用户进行加密保护。
- 不要公开分享 `%APPDATA%\ScreenTranslator\settings.json`。
- 如果使用便携版，不要只移动单独的 `.exe` 文件，解压后的文件夹内容需要保持在一起。
- 安装程序尚未代码签名，Windows 可能显示未知发布者提示。
