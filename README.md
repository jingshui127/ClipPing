# <img width="48" height="48" alt="clipboard" src="https://github.com/user-attachments/assets/45f546a7-ed7b-4d29-838a-8f88bd693247" /> ClipPing

Windows 剪贴板视觉通知工具。每当剪贴板内容更新时，ClipPing 会在当前活动窗口上显示一个短暂的覆盖层动画，给您即时的视觉反馈，确认复制操作已成功。

https://github.com/user-attachments/assets/38db2a32-c694-41a0-b3d8-7532220ffee9

## 安装方式

### Winget（推荐）

```
winget install KevinGosse.ClipPing
```

### 安装包

从[最新发布页](https://github.com/kevingosse/ClipPing/releases/latest)下载 `ClipPing-Setup.exe`。

### 便携版

从[最新发布页](https://github.com/kevingosse/ClipPing/releases/latest)下载 `ClipPing.exe` 直接运行，无需安装。

## 使用方法

ClipPing 在后台运行，系统托盘中会显示一个图标。每次复制内容时，当前活动窗口上会短暂闪烁一个视觉覆盖层。

右键点击托盘图标可访问：
- **设置** - 配置覆盖层外观和行为
- **关于** - 版本信息和链接
- **退出** - 关闭 ClipPing

双击托盘图标可直接打开设置对话框。

## 覆盖层类型

ClipPing 提供 6 种覆盖层样式。您可以在设置对话框中选择偏好的样式并自定义颜色。

| 覆盖层 | 说明 |
|---------|-------------|
| 顶部 | 窗口顶部的渐变条（默认） |
| 底部 | 窗口底部的渐变条 |
| 左侧 | 窗口左侧的渐变条 |
| 右侧 | 窗口右侧的渐变条 |
| 边框 | 窗口四周的实线边框 |
| 光晕 | 窗口四周的发光渐变效果 |

## 设置选项

- **覆盖层颜色** - 使用颜色选择器选取任意颜色
- **覆盖层类型** - 从 6 种覆盖层样式中选择
- **预览** - 应用前实时预览您的设置效果
- **开机自启动** - 登录时自动启动 ClipPing

设置保存在 `%LOCALAPPDATA%\ClipPing\settings.ini`。

## 系统要求

- Windows 10 版本 1607 或更高版本
- x64 架构

## 从源码构建

在 Visual Studio 2025 中打开 `src/ClipPing.sln`，构建 Release/x64 配置。输出文件将放置在 `build/` 目录中。

## 许可证

[MIT](LICENSE)

---

> 本仓库为 [ClipPing](https://github.com/kevingosse/ClipPing) 的汉化版本，由科控物联（QQ:2492123056）维护。
