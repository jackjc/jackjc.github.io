---
layout: wiki
title: Visual Studio Code
categories: Tools
description: Visual Studio Code 的快捷键与使用技巧
keywords: Visual Studio Code
---

## 快捷键

C --> Ctrl

S --> Shift

M --> Alt

Cmd --> Command

| 功能              | Windows | Mac OS X |
|:------------------|:--------|:---------|
| 打开文件          | C-o     |          |
| 打开文件夹        | C-k C-o |          |
| 关闭文件夹        | C-k f   |          |
| 命令面板          | C-S-p   |          |
| 资源管理器        | C-S-e   |          |
| 搜索              | C-S-f   |          |
| Git               | C-S-g   |          |
| 调试              | C-S-d   |          |
| 插件              | C-S-x   |          |
| Markdown 侧边预览 | C-k v   |          |
| Markdown 预览     | C-S-v   |          |

## vim
### 输入法自动切换的问题
1. 安装 [im-select: Switch your input method from terminal](https://github.com/daipeihust/im-select)
2. 配置
```
    "vim.autoSwitchInputMethod.obtainIMCmd": "c:\\\\Windows\\\\System32\\\\im-select.exe",
    "vim.autoSwitchInputMethod.switchIMCmd": "c:\\\\Windows\\\\System32\\\\im-select.exe {im}",
    "vim.autoSwitchInputMethod.defaultIM": "1",
    "vim.autoSwitchInputMethod.enable": true
```

