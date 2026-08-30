<p align="center"><a href="README.md">繁體中文</a> ｜ <strong>English</strong> ｜ <a href="README.ja.md">日本語</a> ｜ <a href="README.ko.md">한국어</a></p>

<h2 align="center">CC69 Threads Manager</h2>
<p align="center"><strong>Clean up your Threads relationships and see who actually follows back.</strong></p>

<p align="center">
  <a href="https://github.com/R69T/CC69_Threads_Public/releases/latest"><strong>⬇️ Download Latest</strong></a>
  &nbsp; · &nbsp;
  <a href="#-quick-start"><strong>🚀 Quick Start</strong></a>
  &nbsp; · &nbsp;
  <a href="#windows-smartscreen"><strong>🛡️ Windows Safety</strong></a>
</p>

## ✨ CC69 at a glance

<p align="center"><img src="assets/EN%20PROM.png" alt="CC69 Threads Manager overview" width="100%"></p>

> **Agreed to follow each other, but your Following and Followers are far apart?** CC69 quickly compares Threads relationships, finds accounts that did not follow back, and makes cleanup easier.

## 🎯 What CC69 does

If you have ever agreed to mutual follows but ended up with Following much higher than Followers, CC69 helps you sort the relationship first:

- 🟠 Accounts you follow that do not follow you back
- 🔴 Followers you have not followed back
- 🟢 Mutual-follow status
- ✅ Select confirmed accounts and unfollow sequentially with visible progress
- 🕒 New-follow protection, default 0 days and user-adjustable
- 📦 Import official Meta / Threads downloaded data when Quick Scan is incomplete
- 🌐 Traditional Chinese / English / Japanese / Korean

### 🙂 A free little bonus

**Mutual Center｜Free Bonus**

A free little extra for everyone. If you are curious, go check it out yourself. Happy mutual follows 🙂

## 🚀 Quick Start

**Sign in → Quick Scan → Review results → Select and clean up**

Quick Scan is limited to **6 runs per rolling 24 hours**.

## ⬇️ Download & Install

Go to **https://github.com/R69T/CC69_Threads_Public/releases/latest**, download `CC69_Threads_Manager_vX.X.X_Windows.zip`, extract it, then run `CC69_Threads_Manager.exe`.

<a id="windows-smartscreen"></a>
## 🛡️ Windows SmartScreen｜Read this before first launch

<p align="center"><img src="assets/windows-smartscreen-real.png" alt="Windows protected your PC - CC69 Threads Manager" width="540"></p>

The image above is the **real Microsoft Defender SmartScreen screen** that may appear the first time CC69 is launched. You may see:

- **Windows protected your PC**
- App: `CC69_Threads_Manager.exe`
- Publisher: **Unknown publisher**

### Why does this appear?

CC69 currently **does not use a commercial Windows Code Signing certificate**. Because of this, Windows cannot verify the publisher through a trusted digital signature, and SmartScreen may also show a warning when an app has not yet built enough reputation.

> **Important: this SmartScreen “unknown publisher” screen by itself does not mean Windows has detected CC69 as a virus.**
>
> It mainly means Windows cannot currently verify the executable through a commercial code-signing certificate / established publisher reputation.

### If you downloaded CC69 from the official GitHub Releases page

First confirm that you downloaded it from this project's official Releases page and that the app name shown by Windows is:

`CC69_Threads_Manager.exe`

Windows may initially show a first SmartScreen screen with only a **Don't run** option. In that case:

1. Click **More info**
2. Confirm the app name is `CC69_Threads_Manager.exe`
3. When **Run anyway** appears, decide whether to continue based on your own verification

### Want to verify the file again? Check SHA-256

Run this in PowerShell:

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

Then compare it with:

`CC69_Threads_Manager.exe.sha256`

included in the Release ZIP. Matching values mean the EXE you have is the same file distributed with that release.

### SmartScreen is different from an actual antivirus detection

If Windows Defender or another antivirus separately reports a **specific malware name, Trojan, Malware, PUA, or other concrete detection**, that is not the same as the SmartScreen “unknown publisher” warning. Do not ignore that kind of alert; verify the source and file separately.

**We recommend downloading CC69 only from this project's official GitHub Releases page.**

## 🔐 Login & Privacy

Your Threads / Meta password is entered on the official Threads / Meta login page, not into the CC69 interface.

## 🔎 If Quick Scan is incomplete

Threads Web uses dynamic loading and virtualized lists. CC69 shows `retrieved count / count displayed by Threads`. If the list remains incomplete, use **Full Data Check** and import your official Meta / Threads downloaded relationship data.

## ⏳ Sequential unfollow

CC69 opens and confirms accounts one by one. Larger selections take longer, so please wait and watch the progress indicator.

## ⚠️ Usage Notice

If Threads shows a challenge, restriction, verification prompt, or “try again later” message, stop and retry later.