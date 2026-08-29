<p align="center"><a href="README.md">繁體中文</a> ｜ <strong>English</strong> ｜ <a href="README.ja.md">日本語</a> ｜ <a href="README.ko.md">한국어</a></p>

# CC69 Threads Manager

**A Windows desktop tool for reviewing and organizing your Threads relationships.**

[⬇️ Download the latest version](https://github.com/R69T/CC69_Threads_Public/releases/latest) · [All releases](https://github.com/R69T/CC69_Threads_Public/releases)

## What it does

- Quick scan of Followers / Following
- Find accounts you follow that do not follow you back
- Find followers you have not followed back
- Show mutual-follow status
- Sequential unfollow with visible progress
- New-follow protection
- Import official Meta / Threads downloaded data for a more complete comparison
- Mutual Follow Center (Beta)
- Local relationship data storage

Quick Scan is limited to **6 runs per rolling 24 hours**.

## Languages

Built in: **繁體中文 / English / 日本語 / 한국어**.

On the first launch, CC69 automatically chooses the UI language from your Windows system language. You can change the language at the top of the app at any time, and CC69 remembers your choice.

## Download and install

Download the latest:

`CC69_Threads_Manager_vX.X.X_Windows.zip`

Then:

1. Extract the ZIP.
2. Run `CC69_Threads_Manager.exe`.
3. On first launch, CC69 prepares its local data.
4. Open Quick Scan and confirm your Threads login.

The ZIP contains the EXE, an EXE SHA-256 file, and a short README. The Release page also provides a SHA-256 file for the ZIP.

## Windows SmartScreen / “Unknown publisher”

CC69 is **not currently signed with a commercial Windows code-signing certificate**. Because of that, Microsoft Defender SmartScreen may show messages such as:

- “Windows protected your PC”
- “Unknown publisher”
- A confirmation before running the app

**This warning by itself does not mean Windows detected a virus.** It mainly means the EXE does not currently have a publisher signature/reputation that Windows can verify.

However, never run an EXE from an unknown source just because this page says so. Only download CC69 from the official Releases page:

https://github.com/R69T/CC69_Threads_Public/releases

You can also verify the EXE SHA-256 in PowerShell:

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

Compare it with `CC69_Threads_Manager.exe.sha256` included in the ZIP.

If the file is from the official Release page and the hash matches, you can review the SmartScreen prompt and choose to run it.

## Login privacy

Login is completed on the official Threads / Meta page. CC69 does not ask you to type your Threads / Meta password into the CC69 interface.

If Threads shows a “Save your login info?” step after login, CC69 attempts to complete that step so the browser login state can be reused later.

## Quick Scan vs complete data import

### Quick Scan

Best for everyday use. It reads relationship data available through Threads Web and shows the number retrieved versus the count displayed by Threads.

Threads uses dynamic loading and virtualized lists, so some accounts may still return incomplete results. CC69 avoids treating missing/unretrieved accounts as confirmed results.

### Full Check by Data Download

For the most complete Followers / Following comparison, download your official Threads data from Meta and import it into CC69. This is the recommended fallback when Quick Scan is incomplete.

## Mutual Follow Center Beta

Participation is voluntary. CC69 can assign previously unmatched participating accounts and process them sequentially. Accounts that are already mutual can be treated as completed instead of as a follow failure.

## Safety notes

Threads page structure and platform limits can change. If Threads displays verification, temporary limits, “try again later,” or another restriction message, stop and try again later.

CC69 does not claim that any action frequency is guaranteed to avoid platform restrictions.
