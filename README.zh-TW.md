[简体中文](README.md) | **繁體中文** | [日本語](README.ja.md) | [English](README.en.md)

# EasyCLIProxyAPI Themes

EasyCLIProxyAPI 自訂主題合集。目前發布版本：**1.0.1**。

| 目錄 | 主題 | 模式 |
| --- | --- | --- |
| `aurora-light` | 霽光·晨曦 2 / Aurora Daylight 2 | 淺色 |
| `aurora-dark` | 霽光·星夜 2 / Aurora Nightfall 2 | 深色 |
| `macos-light` | 經典 macOS·淺色 / Classic macOS Light | 淺色 |
| `macos-dark` | 經典 macOS·深色 / Classic macOS Dark | 深色 |
| `meili-golden-hour` | 梅里·日照金山 / Meili Golden Hour | 深色 |

## 安裝

1. 在 [Releases](https://github.com/Roomen/EasyCLIProxyAPI-Themes/releases/latest) 下載單一主題 ZIP，或下載 `EasyCLIProxyAPI-Themes-v1.0.1.zip` 合集。
2. 在 EasyCLIProxyAPI 中開啟「外觀」→「開啟主題資料夾」。
3. 解壓縮 ZIP，將所需主題資料夾直接放入該目錄，保持 `<主題目錄>/<主題資料夾>/theme.json` 的結構。
4. 返回應用程式，點擊「重新載入」，選擇「自訂主題」並啟用主題。

也可從本儲存庫根目錄複製所需主題資料夾。請勿只複製 JSON；梅里主題需要一併複製 `assets/meili.jpg`。應用程式不會直接讀取 ZIP 檔案。

Aurora 與經典 macOS 主題會要求原生透明材質，不支援的平台會使用備用效果。梅里主題需要支援自訂主題背景圖片的應用程式版本；背景圖片會依視窗比例裁切。

## 版本與檔案

版本透過 Git tag 與 Release 管理。`theme.json` 保持標準 JSON，不新增註解或額外版本欄位。原始碼儲存庫保存主題檔案，壓縮包僅作為 Release 附件發布；`SHA256SUMS.txt` 用於核對下載檔案。
