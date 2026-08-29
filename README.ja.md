<p align="center"><a href="README.md">繁體中文</a> ｜ <a href="README.en.md">English</a> ｜ <strong>日本語</strong> ｜ <a href="README.ko.md">한국어</a></p>

<h2 align="center">CC69 Threads Manager</h2>
<p align="center"><strong>Threads のフォロー関係を見やすく整理。</strong></p>

<p align="center">
  <a href="https://github.com/R69T/CC69_Threads_Public/releases/latest"><strong>⬇️ 最新版をダウンロード</strong></a>
  &nbsp; · &nbsp;
  <a href="#-クイックスタート"><strong>🚀 クイックスタート</strong></a>
  &nbsp; · &nbsp;
  <a href="#%EF%B8%8F-windows-smartscreen"><strong>🛡️ Windows 安全案内</strong></a>
</p>

## ✨ CC69 の機能紹介

<p align="center"><img src="assets/cc69-promo-ja.webp" alt="CC69 Threads Manager 機能紹介" width="100%"></p>

> **相互フォローのはずなのに、フォロー数とフォロワー数の差が大きい？** CC69 が Threads のフォロー関係をすばやく比較し、フォローバックされていないアカウントを見つけて、整理・解除をラクにします。

## 🎯 CC69 でできること

相互フォローの約束をしたのに、いつの間にか Following が Followers より大幅に増えてしまった場合、CC69 でまず関係を整理できます。

- 🟠 自分はフォローしているが、相手はフォローバックしていない
- 🔴 相手はフォローしているが、自分がまだフォロー返ししていない
- 🟢 相互フォロー状態
- ✅ 確認済みアカウントを選択し、進捗を表示しながら順番にフォロー解除
- 🕒 新規フォロー保護：初期値 0 日、自由に変更可能
- 📦 クイックスキャンが不完全な場合は Meta / Threads 公式ダウンロードデータを読み込み
- 🌐 繁體中文 / English / 日本語 / 한국어

### 🙂 無料のおまけ

**相互フォローセンター｜無料のおまけ**

みんな向けの無料の小機能です。気になる方は自分で見てみてください。楽しい相互フォローを 🙂

## 🚀 クイックスタート

**ログイン → クイックスキャン → 結果確認 → 選択して整理**

クイックスキャンは **24時間のローリング期間で最大6回**です。

## ⬇️ ダウンロードとインストール

**https://github.com/R69T/CC69_Threads_Public/releases/latest** から `CC69_Threads_Manager_vX.X.X_Windows.zip` をダウンロードし、展開後 `CC69_Threads_Manager.exe` を実行してください。

## 🛡️ Windows SmartScreen

<p align="center"><img src="assets/windows-smartscreen-ja.svg" alt="Windows SmartScreen の操作案内" width="100%"></p>

CC69 は現在、**商用 Windows コード署名証明書で署名されていません**。そのため初回実行時に「Windows によって PC が保護されました」や「不明な発行元」と表示される場合があります。

> **この SmartScreen 画面そのものは、Windows がウイルスを検出したという意味ではありません。** Windows が信頼済みのデジタル署名／発行元の評判情報から CC69 の発行元を確認できない、という意味です。

本プロジェクトの公式 GitHub Releases からダウンロードした場合：

1. **「詳細情報」**をクリックします。
2. アプリ名が `CC69_Threads_Manager.exe` であることを確認します。
3. **「実行」**をクリックします。

必ず公式 Releases からダウンロードしてください。必要に応じて SHA-256 も確認できます。

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

Release パッケージ内の `CC69_Threads_Manager.exe.sha256` と比較してください。

> Windows Defender や別のウイルス対策ソフトが、SmartScreen とは別に具体的なマルウェア検出を表示した場合は別の警告です。無視せず確認してください。

## 🔐 ログインとプライバシー

Threads / Meta のパスワードは公式ログインページで入力します。CC69 自体の画面にパスワードを入力する方式ではありません。

## 🔎 クイックスキャンが不完全な場合

Threads Web は動的ロードと仮想リストを使用しています。不完全な場合は **完全データ確認** に切り替え、Meta / Threads 公式ダウンロードデータを読み込んでください。

## ⏳ フォロー解除について

CC69 はアカウントを1件ずつ開いて確認するため、選択数が多いほど時間がかかります。開始後は進捗を確認しながらお待ちください。

## ⚠️ 使用上の注意

Threads に認証、制限、「後でもう一度お試しください」などが表示された場合は操作を停止し、時間を置いて再試行してください。
