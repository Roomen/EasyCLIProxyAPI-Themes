[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [English](README.en.md)

# EasyCLIProxyAPI Themes

A collection of custom themes for EasyCLIProxyAPI. Current release: **1.0.1**.

| Directory | Theme | Appearance |
| --- | --- | --- |
| `aurora-light` | Aurora Daylight 2 | Light |
| `aurora-dark` | Aurora Nightfall 2 | Dark |
| `macos-light` | Classic macOS Light | Light |
| `macos-dark` | Classic macOS Dark | Dark |
| `meili-golden-hour` | Meili Golden Hour | Dark |

## Installation

1. Download an individual theme ZIP or the full collection, `EasyCLIProxyAPI-Themes-v1.0.1.zip`, from [Releases](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest).
2. In EasyCLIProxyAPI, open **Appearance → Open themes folder**.
3. Extract the ZIP and place the desired theme folders directly in that directory. Keep the structure `<themes directory>/<theme folder>/theme.json`.
4. Return to the app, click **Reload**, and select and enable a theme under **Custom themes**.

You can also copy theme folders from this repository's `themes/` directory. Copy the entire folder, including its assets; Meili Golden Hour also requires `assets/meili.jpg`. The app does not read ZIP files directly.

Aurora and Classic macOS themes request native translucent materials, with fallback effects on unsupported platforms. Meili Golden Hour requires an app build with custom theme background-image support. The background image is cropped to fit the window's aspect ratio.

## Versions and files

Versions are managed through Git tags and Releases. `theme.json` remains standard JSON, without comments or extra version fields. Theme files are stored in the source repository; ZIP archives are published only as Release assets. Use `SHA256SUMS.txt` to verify downloaded files.
