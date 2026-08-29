<p align="center">
  <img src="assets/cc69-banner.svg" alt="CC69 Social Platform Manager" width="100%">
</p>

<p align="center">
  <strong>繁體中文</strong> ｜ <a href="README.en.md">English</a> ｜ <a href="README.ja.md">日本語</a> ｜ <a href="README.ko.md">한국어</a>
</p>

<p align="center">
  <strong>CC69 Threads Manager</strong><br>
  Windows 上更清楚地整理你的 Threads 追蹤關係。
</p>

<p align="center">
  <a href="https://github.com/R69T/CC69_Threads_Public/releases/latest"><strong>⬇️ 下載最新版本</strong></a>
  &nbsp;｜&nbsp;
  <a href="https://github.com/R69T/CC69_Threads_Public/releases">所有版本</a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Threads-目前支援-238636?style=for-the-badge" alt="Threads supported">
  <img src="https://img.shields.io/badge/Windows-桌面程式-1f6feb?style=for-the-badge" alt="Windows">
  <img src="https://img.shields.io/badge/繁中%20%7C%20EN%20%7C%20日本語%20%7C%20한국어-4%20Languages-6f42c1?style=for-the-badge" alt="4 languages">
</p>

---

# CC69 是什麼？

如果你經營 Threads，一旦 Following / Followers 變多，就很難靠人工確認：

- 我追蹤了誰，但對方沒有回追？
- 誰有追蹤我，但我還沒回追？
- 哪些帳號已經互追？
- 哪些是最近才追蹤，不想太快取消？

**CC69 Threads Manager 是 Windows 桌面工具，把這些關係整理集中在同一個介面。**

目前正式支援 Threads；YouTube、Twitch 等平台屬於後續規劃。

---

# 🌐 語言

程式內建：

**繁體中文 / English / 日本語 / 한국어**

第一次啟動時會依 **Windows 系統語言自動選擇介面語言**：

- 中文 Windows → 繁體中文
- English / 其他語言 → English
- 日本語 Windows → 日本語
- 한국어 Windows → 한국어

之後可在程式最上方隨時切換，CC69 會記住你的選擇。

---

# ✨ 主要功能

| 功能 | 用途 |
| --- | --- |
| **快速檢查** | 直接從 Threads Web 取得目前可讀取的 Followers / Following 關係。 |
| **沒回追我** | 找出「我有追蹤，但對方沒有追蹤我」的帳號。 |
| **我沒回追** | 找出「對方追蹤我，但我尚未追蹤對方」的帳號。 |
| **互追狀態** | 顯示哪些帳號已經雙向追蹤。 |
| **依序取消追蹤** | 勾選帳號後逐一處理，並顯示目前進度。 |
| **新追蹤保護** | 可設定保護天數，降低剛追蹤就被整理掉的情況。 |
| **完整資料匯入** | 匯入 Meta / Threads 官方下載資料，做較完整的關係比對。 |
| **互追中心 Beta** | 自願加入互追配對，取得尚未配過的參與帳號。 |
| **登入狀態保存** | 第一次登入完成後，之後通常不需要每次重新登入。 |
| **本機資料** | 關係整理與操作狀態主要保存在使用者自己的電腦。 |

快速檢查目前設有 **滾動 24 小時最多 6 次**的使用上限，避免短時間內過度重複掃描。

---

# ⬇️ 下載與安裝

前往：

**https://github.com/R69T/CC69_Threads_Public/releases/latest**

下載最新版本中的：

`CC69_Threads_Manager_vX.X.X_Windows.zip`

然後：

1. 解壓縮 ZIP。
2. 執行 `CC69_Threads_Manager.exe`。
3. 第一次開啟時，CC69 會建立必要的本機資料。
4. 到「快速檢查」確認 Threads 登入。
5. 完成後即可開始掃描與整理。

ZIP 內會附：

- `CC69_Threads_Manager.exe`
- EXE SHA-256 核對檔
- `README.txt`

Release 頁另外提供 ZIP 的 SHA-256 核對檔。

---

# 🛡️ Windows 顯示「未知的發行者」／SmartScreen 是什麼？

目前 CC69 **尚未使用商業程式碼簽章憑證（Code Signing Certificate）簽署 Windows EXE**。

因此 Windows Defender SmartScreen 可能顯示：

- 「Windows 已保護您的電腦」
- 「未知的發行者」
- 或要求你確認是否仍要執行

**這個畫面本身不代表 Windows 已偵測到病毒。** 它主要代表目前這個 EXE 沒有 Windows 能驗證的發行者數位簽章／聲譽不足。

但同樣重要的是：**不要因為看到這段說明就執行任何來源不明的 EXE。** 請只從本專案官方 GitHub Releases 下載，並可使用 SHA-256 驗證檔案。

官方下載來源：

**https://github.com/R69T/CC69_Threads_Public/releases**

如果你已確認檔案是從這裡下載、SHA-256 也正確，而 Windows 顯示 SmartScreen 提示，你可以依 Windows 畫面選擇「仍要執行」。

## SHA-256 驗證（Windows PowerShell）

在 ZIP 或 EXE 所在資料夾開啟 PowerShell：

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

將結果與 ZIP 內附的：

`CC69_Threads_Manager.exe.sha256`

進行比對。

> 未來若專案導入正式 Windows Code Signing，這類「未知的發行者」提示可望明顯減少。

---

# 🔐 Threads / Meta 登入方式

登入是在 **Threads / Meta 官方頁面**完成。

CC69 不會要求你把 Threads / Meta 密碼輸入到 CC69 自己的介面。

第一次登入時，如果 Threads 顯示：

**「儲存你的登入資料？」**

CC69 會嘗試自動完成「儲存資料」流程，以便之後直接沿用瀏覽器登入狀態。

---

# 🔎 快速檢查 vs 完整資料檢查

## 快速檢查

適合日常使用，不需要先下載資料。

Threads Web 採用動態載入與虛擬清單。CC69 會盡可能累積瀏覽器實際取得的 Followers / Following 資料，並顯示：

`已取得數量 / Threads 顯示總數`

但部分帳號仍可能遇到快速掃描不完整。

如果 Followers 不完整，CC69 會限制危險的退追判斷；如果 Following 只有部分取得，也不會把「尚未取得」的帳號當成已確認結果。

## 手動下載資訊完整檢查

需要更完整的關係比對時，建議從 Meta 官方下載自己的 Threads 資料，再匯入 CC69。

這是快速檢查不完整時的推薦方案。

---

# 🤝 互追中心 Beta

互追中心採 **自願加入**。

加入後，CC69 會協助取得尚未配對過的其他參與帳號，再逐一確認追蹤。

已經互追的帳號可直接視為完成，不會因為不能再次按「追蹤」而被當成錯誤。

這項功能仍在測試階段。

---

# ⚠️ 使用提醒

Threads 網頁結構與平台限制可能隨時改變，因此部分功能未來可能需要跟著更新。

所有追蹤與取消追蹤操作都應由使用者主動確認。如果 Threads 顯示驗證、限制、稍後再試或其他異常訊息，請停止操作並稍後再使用。

CC69 不保證任何操作頻率一定不會觸發平台限制。

---

# 開發方向

| 平台 | 狀態 |
| --- | --- |
| **Threads** | ✅ 目前支援 |
| **YouTube** | 🛠️ 規劃中 |
| **Twitch** | 🛠️ 規劃中 |
| **其他平台** | 💡 評估中 |

<p align="center">
  <strong>CC69 Social Platform Manager</strong><br>
  Threads first. More platforms coming later.
</p>
