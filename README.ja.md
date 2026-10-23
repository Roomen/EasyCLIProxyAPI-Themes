[简体中文](README.md) | [繁體中文](README.zh-TW.md) | [日本語](README.ja.md) | [English](README.en.md)

# EasyCLIProxyAPI Themes

EasyCLIProxyAPI のカスタムテーマ集です。現在のリリースバージョン：**1.0.1**。

| ディレクトリ | テーマ | モード |
| --- | --- | --- |
| `aurora-light` | オーロラ・朝 2 / Aurora Daylight 2 | ライト |
| `aurora-dark` | オーロラ・夜 2 / Aurora Nightfall 2 | ダーク |
| `macos-light` | クラシック macOS・ライト / Classic macOS Light | ライト |
| `macos-dark` | クラシック macOS・ダーク / Classic macOS Dark | ダーク |
| `meili-golden-hour` | 梅里・黄金の朝 / Meili Golden Hour | ダーク |

## インストール

1. [Releases](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest) から個別テーマの ZIP、または全テーマをまとめた `EasyCLIProxyAPI-Themes-v1.0.1.zip` をダウンロードします。
2. EasyCLIProxyAPI で「外観」→「テーマフォルダーを開く」を選択します。
3. ZIP を展開し、必要なテーマフォルダーをそのディレクトリに直接配置します。`<テーマディレクトリ>/<テーマフォルダー>/theme.json` の構造を維持してください。
4. アプリに戻り、「再読み込み」をクリックして「カスタムテーマ」からテーマを選択し、有効にします。

このリポジトリの `themes/` からテーマフォルダーをコピーすることもできます。JSON だけをコピーしないでください。梅里テーマには `assets/meili.jpg` も必要です。アプリは ZIP ファイルを直接読み込みません。

Aurora とクラシック macOS テーマはネイティブの透明マテリアルを要求します。非対応のプラットフォームでは代替の表示効果を使用します。梅里テーマには、カスタムテーマの背景画像に対応したアプリのビルドが必要です。背景画像はウィンドウの縦横比に合わせてトリミングされます。

## バージョンとファイル

バージョンは Git tag と Release で管理します。`theme.json` は標準 JSON のままとし、コメントや追加のバージョンフィールドは加えません。ソースリポジトリにはテーマファイルを保存し、圧縮ファイルは Release の添付ファイルとしてのみ公開します。`SHA256SUMS.txt` でダウンロードしたファイルを検証できます。
