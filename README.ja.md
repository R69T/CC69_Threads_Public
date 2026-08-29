<p align="center"><a href="README.md">繁體中文</a> ｜ <a href="README.en.md">English</a> ｜ <strong>日本語</strong> ｜ <a href="README.ko.md">한국어</a></p>

# CC69 Threads Manager

**Threads のフォロー関係を確認・整理するための Windows デスクトップアプリです。**

[⬇️ 最新版をダウンロード](https://github.com/R69T/CC69_Threads_Public/releases/latest) · [すべてのリリース](https://github.com/R69T/CC69_Threads_Public/releases)

## 主な機能

- Followers / Following のクイックスキャン
- 自分はフォローしているが、相手がフォローしていないアカウントを確認
- 相手はフォローしているが、自分がまだフォローしていないアカウントを確認
- 相互フォロー状態の表示
- 選択したアカウントを順番にフォロー解除し、進捗を表示
- 新規フォロー保護
- Meta / Threads の公式ダウンロードデータを読み込み、より完全な比較
- 相互フォローセンター（Beta）
- 関係データを主にローカルに保存

クイックスキャンは **24 時間のローリング期間で最大 6 回**です。

## 言語

**繁體中文 / English / 日本語 / 한국어** を内蔵しています。

初回起動時は Windows のシステム言語から自動的に UI 言語を選択します。その後はアプリ上部からいつでも変更でき、選択内容も保存されます。

## ダウンロードとインストール

最新版の：

`CC69_Threads_Manager_vX.X.X_Windows.zip`

をダウンロードし、次の手順で使用します。

1. ZIP を展開します。
2. `CC69_Threads_Manager.exe` を実行します。
3. 初回起動時に CC69 が必要なローカルデータを準備します。
4. 「クイックスキャン」で Threads ログインを確認します。

ZIP には EXE、EXE の SHA-256 ファイル、簡単な README が含まれます。Release ページには ZIP 自体の SHA-256 もあります。

## Windows SmartScreen / 「不明な発行元」について

現在の CC69 は、**商用の Windows コード署名証明書で EXE を署名していません**。

そのため Microsoft Defender SmartScreen が：

- 「Windows によって PC が保護されました」
- 「不明な発行元」
- 実行前の確認

を表示する場合があります。

**この警告だけでウイルスが検出されたという意味ではありません。** 主に、Windows が確認できる発行者署名や十分なアプリ評価情報がないことを示します。

ただし、出所不明の EXE を実行しないでください。CC69 は必ず公式 Releases から入手してください：

https://github.com/R69T/CC69_Threads_Public/releases

PowerShell で SHA-256 を確認できます：

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

ZIP 内の `CC69_Threads_Manager.exe.sha256` と比較してください。

## ログインとプライバシー

ログインは Threads / Meta の公式ページで行います。CC69 の画面に Threads / Meta のパスワードを入力する必要はありません。

ログイン後に「ログイン情報を保存しますか？」に相当する画面が表示された場合、CC69 はブラウザーのログイン状態を再利用できるよう、その手順の完了を試みます。

## クイックスキャンと完全データチェック

### クイックスキャン

日常の確認向けです。Threads Web から取得できる Followers / Following 情報を読み取り、取得件数と Threads が表示する件数を比較します。

Threads は動的読み込みと仮想リストを使用しているため、一部のアカウントでは不完全な結果になる可能性があります。CC69 は未取得のアカウントを確認済み結果として扱いません。

### ダウンロードデータで完全チェック

より完全な Followers / Following 比較が必要な場合は、Meta から自分の Threads データをダウンロードして CC69 に読み込んでください。クイックスキャンが不完全な場合の推奨方法です。

## 相互フォローセンター Beta

参加は任意です。CC69 はまだ組み合わせたことのない参加アカウントを割り当て、順番に処理できます。すでに相互フォロー済みの場合は、追跡失敗ではなく完了として扱えます。

## 使用上の注意

Threads のページ構造や制限は変更される可能性があります。認証、制限、「後でもう一度お試しください」などが表示された場合は操作を停止し、時間を置いてから再度使用してください。

CC69 は、特定の操作頻度でプラットフォーム制限を必ず回避できるとは保証しません。
