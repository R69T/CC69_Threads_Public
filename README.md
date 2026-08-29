<p align="center"><img src="assets/cc69-banner.svg" alt="CC69 Threads Manager" width="100%"></p>

<p align="center"><strong>繁體中文</strong> ｜ <a href="README.en.md">English</a> ｜ <a href="README.ja.md">日本語</a> ｜ <a href="README.ko.md">한국어</a></p>

<h2 align="center">CC69 Threads Manager</h2>
<p align="center"><strong>誰沒回追你？誰追蹤你但你還沒回追？一次整理清楚。</strong></p>

<p align="center">
  <a href="https://github.com/R69T/CC69_Threads_Public/releases/latest"><strong>⬇️ 下載最新版</strong></a>
  &nbsp; · &nbsp;
  <a href="#-快速開始"><strong>🚀 快速開始</strong></a>
  &nbsp; · &nbsp;
  <a href="#-windows-smartscreen"><strong>🛡️ Windows 安全提示</strong></a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Windows-Desktop-1f6feb?style=for-the-badge">
  <img src="https://img.shields.io/badge/Threads-Supported-238636?style=for-the-badge">
  <img src="https://img.shields.io/badge/繁中%20%7C%20EN%20%7C%20日本語%20%7C%20한국어-4%20Languages-6f42c1?style=for-the-badge">
</p>

---

## ✨ CC69 功能介紹

<p align="center"><img src="assets/cc69-promo-zh.webp" alt="CC69 Threads Manager 功能介紹" width="100%"></p>

> **說好互追，結果追蹤數和粉絲數差很大？** CC69 幫你快速比對 Threads 追蹤關係，找出沒回追的帳號，**清除更省事**。

---

## 🎯 這個程式主要做什麼？

如果你曾經遇過「明明說好互追，最後 Following 卻遠高於 Followers」，CC69 可以先幫你把追蹤關係整理清楚：

- 🟠 **我追蹤，但對方沒回追我**
- 🔴 **對方追蹤我，但我還沒回追**
- 🟢 **已互相追蹤**
- ✅ **選取確認過的帳號後依序取消追蹤**
- 🕒 **新追蹤保護**：預設 0 天，可自行調整
- 📦 **快速檢查不完整時，可改用官方下載資料做完整比對**

操作順序很簡單：**先登入 → 開始檢查 → 查看結果 → 選取整理**。

### 🙂 免費小彩蛋

**互追中心｜免費小彩蛋**

給大家免費的小功能，有興趣就自己去了解看看。祝大家互追快樂 🙂

---

## 🚀 快速開始

| 步驟 | 要做什麼 | 你會看到什麼 |
| --- | --- | --- |
| **1. 啟動 CC69** | 解壓縮 ZIP 後執行 `CC69_Threads_Manager.exe` | CC69 會先顯示啟動／初始化畫面。 |
| **2. 確認 Threads 登入** | 按藍色「確認 Threads 登入」 | 在 Threads / Meta 官方頁面完成登入。 |
| **3. 開始快速檢查** | 登入成功後按「開始快速檢查」 | 顯示 Followers / Following 已取得進度。 |
| **4. 查看結果** | 查看統計卡與下方表格 | 追蹤中、粉絲、沒回追、我沒回追、互追。 |
| **5. 整理帳號** | 選取已確認的沒回追帳號 | CC69 逐一處理並顯示取消追蹤進度。 |

第一次使用最重要的一件事：**先登入，再掃描。**

---

## ✨ 主要功能

- 🔎 **快速檢查**：直接透過 Threads Web 讀取目前可取得的 Followers / Following。
- 🟠 **沒回追我**：找出「我有追蹤，但對方沒有追蹤我」。
- 🔴 **我沒回追**：找出「對方追蹤我，但我尚未追蹤對方」。
- 🟢 **互追**：顯示雙向追蹤狀態。
- ✅ **依序取消追蹤**：選取後逐一處理，並持續顯示目前進度。
- 🕒 **新追蹤保護**：預設 **0 天＝不保護**。例如設為 7 天，最近 7 天才追蹤的帳號不會列入退追整理。
- 📦 **完整資料檢查**：快速檢查不完整時，可匯入 Meta / Threads 官方下載資料。
- 🌐 **四語系**：繁體中文 / English / 日本語 / 한국어；第一次啟動依 Windows 系統語言自動選擇。

快速檢查目前限制為 **滾動 24 小時最多 6 次**。

---

## 🖥️ 顯示器與視窗

CC69 會依 Windows 目前螢幕的可用工作區與顯示縮放比例調整第一次開啟的視窗大小。小型／高縮放螢幕會壓縮上方資訊區；較大螢幕則把更多空間留給下方結果表格。

---

## ⬇️ 下載與安裝

最新版：**https://github.com/R69T/CC69_Threads_Public/releases/latest**

下載 `CC69_Threads_Manager_vX.X.X_Windows.zip`，解壓縮後執行 `CC69_Threads_Manager.exe`。

Release 會附 SHA-256 核對檔。

---

## 🛡️ Windows SmartScreen

CC69 目前尚未使用商業 Windows Code Signing 憑證簽署 EXE，所以 Windows 可能顯示「Windows 已保護您的電腦」或「未知的發行者」。

**這個提示本身不代表 Windows 已偵測到病毒。** 它代表 Windows 目前無法驗證這個 EXE 的發行者數位簽章／聲譽。

請只從本 GitHub 官方 Releases 下載。

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

可與 ZIP 內的 `CC69_Threads_Manager.exe.sha256` 比對。

---

## 🔐 登入與隱私

Threads / Meta 密碼是在**官方登入頁面**輸入，不是在 CC69 自己的介面輸入。第一次登入後，如果 Threads 顯示「儲存你的登入資料？」流程，CC69 會嘗試完成儲存，讓之後通常不需要每次重新登入。

---

## 🔎 快速檢查不完整怎麼辦？

Threads Web 使用動態載入與虛擬清單。CC69 會顯示 `已取得數量 / Threads 顯示總數`。如果快速檢查仍不完整，切換到 **完整資料檢查**，再匯入 Meta / Threads 官方下載資料。

---

## ⏳ 取消追蹤需要多久？

CC69 會逐一開啟並確認每個帳號，因此選取帳號越多，處理時間越長。開始後請耐心等待並查看程式內進度。

---

## ⚠️ 使用提醒

Threads 的頁面結構與平台限制可能隨時更新。若 Threads 顯示驗證、限制、稍後再試或其他異常，請停止操作並稍後再使用。

<p align="center"><strong>CC69 Threads Manager</strong><br>Threads first. More platforms later.</p>
