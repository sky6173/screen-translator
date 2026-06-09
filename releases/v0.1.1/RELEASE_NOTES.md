# 屏幕翻译 0.1.1

这是第一个按正式安装包流程发布的 Windows 版本。已完成本地安装、启动、基础功能和卸载测试。

## 下载

推荐下载 Windows 安装包：

- [screen-translator-0.1.1-win-x64-setup.exe](https://github.com/sky6173/screen-translator/releases/download/v0.1.1/screen-translator-0.1.1-win-x64-setup.exe)

便携版用于临时运行或不想安装的场景：

- [screen-translator-0.1.1-win-x64.zip](https://github.com/sky6173/screen-translator/releases/download/v0.1.1/screen-translator-0.1.1-win-x64.zip)

## 校验值

如果需要确认文件完整性，可以对照下面的 SHA256：

- 安装包：`1970627b3c9df7d73797fb4da750088774180b74a7ddd552ed7219b6e7b10388`
- 便携版：`a3a0aed78eb720c008e5d87c9ec71f46f55b01b0e2936a9d31621f36ce0ab37e`

## 本版重点

- 使用中文安装向导，支持选择安装目录。
- 卸载时会清理安装器创建的程序文件夹和快捷方式。
- 继续保留便携版 zip，方便不安装时临时运行。
- API Key 保存在本机，并使用 Windows 当前用户 DPAPI 保护。

## 已知提示

- 当前安装包还没有代码签名，Windows 可能会显示未知发布者提示。
- 使用模型获取和翻译功能前，需要先在设置里填写可用的 API Key。
