**简体中文** | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [English](README.en.md)

# EasyCLIProxyAPI Themes

EasyCLIProxyAPI 自定义主题合集。可通过 [Latest Release](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest) 获取最新版本。

| 目录 | 主题 | 模式 |
| --- | --- | --- |
| `aurora-light` | 霁光·晨曦 2 / Aurora Daylight 2 | 浅色 |
| `aurora-dark` | 霁光·星夜 2 / Aurora Nightfall 2 | 深色 |
| `macos-light` | 经典 macOS·浅色 / Classic macOS Light | 浅色 |
| `macos-dark` | 经典 macOS·深色 / Classic macOS Dark | 深色 |
| `meili-golden-hour` | 梅里·日照金山 / Meili Golden Hour | 深色 |
| `paw-in-paw-light` | 猫爪相依·暖色 / Paw in Paw Light | 浅色 |
| `curious-cats-dark` | 双猫凝望·暗色 / Curious Cats Dark | 深色 |

## 安装

1. 在 [Releases 最新发布页](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest) 下载单主题 ZIP，或直接下载 [全主题合集 ZIP (EasyCLIProxyAPI-Themes.zip)](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest/download/EasyCLIProxyAPI-Themes.zip)。
2. 在 EasyCLIProxyAPI 中打开「外观」→「打开主题目录」。
3. 解压 ZIP，将所需主题文件夹直接放入该目录，保持 `<主题目录>/<主题文件夹>/theme.json` 的结构。
4. 返回应用，点击「重新加载」，选择「自定义主题」并启用主题。

也可从本仓库根目录复制所需主题文件夹。不要只复制 JSON；梅里主题需要一起复制 `assets/meili.jpg`。应用不直接读取 ZIP 文件。

Aurora 与经典 macOS 主题请求原生透明材质，不支持的平台使用回退效果。梅里主题需要支持自定义主题背景图片的应用构建；背景图片按窗口比例裁剪。

## 版本与文件

版本通过 Git tag 和 Release 管理。`theme.json` 保持标准 JSON，不添加注释或额外版本字段。源码仓库保存主题文件，压缩包仅作为 Release 附件发布；`SHA256SUMS.txt` 用于核对下载文件。

