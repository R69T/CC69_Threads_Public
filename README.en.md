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
## 🛡️ Windows SmartScreen

<p align="center"><img src="assets/windows-smartscreen-real.png" alt="Windows protected your PC - CC69 Threads Manager" width="540"></p>

The screenshot above is the **real Microsoft Defender SmartScreen screen** that may appear when CC69 is launched for the first time. It may show the app as `CC69_Threads_Manager.exe` with an **unknown publisher**.

CC69 is currently **not signed with a commercial Windows Code Signing certificate**, so Windows cannot verify the publisher through a trusted digital signature.

> **This SmartScreen screen by itself does not mean Windows detected CC69 as a virus.** It mainly means the executable does not currently have a Windows-verifiable commercial code-signing certificate / established publisher reputation.

If you downloaded CC69 from this project's **official GitHub Releases** page, confirm that the application is `CC69_Threads_Manager.exe` and then decide whether to continue from the Windows prompt.

You can also verify the executable with SHA-256:

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

Compare the result with `CC69_Threads_Manager.exe.sha256` included with the release package.

> If Windows Defender or another antivirus separately reports a **specific malware name or detection**, that is different from the SmartScreen “unknown publisher” warning and should be investigated separately.

## 🔐 Login & Privacy

Your Threads / Meta password is entered on the official Threads / Meta login page, not into the CC69 interface.

## 🔎 If Quick Scan is incomplete

Threads Web uses dynamic loading and virtualized lists. CC69 shows `retrieved count / count displayed by Threads`. If the list remains incomplete, use **Full Data Check** and import your official Meta / Threads downloaded relationship data.

## ⏳ Sequential unfollow

CC69 opens and confirms accounts one by one. Larger selections take longer, so please wait and watch the progress indicator.

## ⚠️ Usage Notice

If Threads shows a challenge, restriction, verification prompt, or “try again later” message, stop and retry later.