<p align="center"><a href="README.md">繁體中文</a> ｜ <a href="README.en.md">English</a> ｜ <a href="README.ja.md">日本語</a> ｜ <strong>한국어</strong></p>

<h2 align="center">CC69 Threads Manager</h2>
<p align="center"><strong>Threads 팔로우 관계를 한눈에 정리하세요.</strong></p>

<p align="center">
  <a href="https://github.com/R69T/CC69_Threads_Public/releases/latest"><strong>⬇️ 최신 버전 다운로드</strong></a>
  &nbsp; · &nbsp;
  <a href="#-빠른-시작"><strong>🚀 빠른 시작</strong></a>
  &nbsp; · &nbsp;
  <a href="#windows-smartscreen"><strong>🛡️ Windows 안전 안내</strong></a>
</p>

## ✨ CC69 기능 소개

<p align="center"><img src="assets/KR%20PROM.png" alt="CC69 Threads Manager 기능 소개" width="100%"></p>

> **맞팔하기로 했는데 팔로잉 수와 팔로워 수 차이가 너무 큰가요?** CC69가 Threads 팔로우 관계를 빠르게 비교해 맞팔하지 않은 계정을 찾고 더 쉽게 정리할 수 있게 도와줍니다.

## 🎯 CC69가 하는 일

서로 맞팔하기로 했는데 시간이 지나면서 Following이 Followers보다 훨씬 많아졌다면, CC69로 먼저 관계를 정리할 수 있습니다.

- 🟠 내가 팔로우하지만 상대가 나를 맞팔하지 않은 계정
- 🔴 상대는 나를 팔로우하지만 내가 아직 맞팔하지 않은 계정
- 🟢 맞팔 상태
- ✅ 확인된 계정을 선택한 뒤 진행률을 보면서 순차 언팔로우
- 🕒 신규 팔로우 보호: 기본 0일, 사용자가 직접 조정 가능
- 📦 빠른 검사가 불완전하면 Meta / Threads 공식 다운로드 데이터 가져오기
- 🌐 繁體中文 / English / 日本語 / 한국어

### 🙂 무료 작은 보너스

**맞팔 센터｜무료 작은 보너스**

모두를 위한 무료 작은 기능입니다. 궁금하시면 직접 둘러보세요. 즐거운 맞팔 되세요 🙂

## 🚀 빠른 시작

**로그인 → 빠른 검사 → 결과 확인 → 선택 후 정리**

빠른 검사는 **최근 24시간 기준 최대 6회**입니다.

## ⬇️ 다운로드 및 설치

**https://github.com/R69T/CC69_Threads_Public/releases/latest** 에서 `CC69_Threads_Manager_vX.X.X_Windows.zip`을 다운로드하고 압축을 푼 뒤 `CC69_Threads_Manager.exe`를 실행하세요.

<a id="windows-smartscreen"></a>
## 🛡️ Windows SmartScreen｜처음 실행하기 전에 확인하세요

<p align="center"><img src="assets/windows-smartscreen-real.png" alt="Windows의 PC 보호 - CC69 Threads Manager" width="540"></p>

위 이미지는 CC69를 처음 실행할 때 **실제로 표시될 수 있는 Microsoft Defender SmartScreen 화면**입니다. 다음과 같은 내용이 표시될 수 있습니다.

- **Windows의 PC 보호**
- 앱: `CC69_Threads_Manager.exe`
- 게시자: **알 수 없는 게시자 / Unknown publisher**

### 왜 이 화면이 나타나나요?

CC69는 현재 **상용 Windows Code Signing 코드 서명 인증서를 사용하지 않습니다**. 따라서 Windows가 신뢰할 수 있는 디지털 서명을 통해 게시자 신원을 확인할 수 없습니다. 또한 앱이 아직 충분한 SmartScreen 평판을 쌓지 못한 경우에도 이 경고가 표시될 수 있습니다.

> **중요: 이 SmartScreen의 “알 수 없는 게시자” 화면 자체가 Windows에서 CC69를 바이러스로 탐지했다는 뜻은 아닙니다.**
>
> 주로 Windows가 상용 코드 서명 인증서 / 기존 게시자 평판으로 이 EXE의 게시자를 확인할 수 없다는 의미입니다.

### 이 프로젝트의 공식 GitHub Releases에서 다운로드했다면

먼저 이 프로젝트의 공식 Releases에서 다운로드했는지 확인하고, Windows 화면에 표시된 앱 이름이 다음과 같은지 확인하세요.

`CC69_Threads_Manager.exe`

Windows가 처음에 **실행 안 함**만 표시하는 SmartScreen 화면을 보여 준다면:

1. **추가 정보**를 클릭합니다
2. 앱 이름이 `CC69_Threads_Manager.exe`인지 확인합니다
3. **실행** 또는 **계속 실행**에 해당하는 옵션이 나타나면, 직접 확인한 뒤 실행 여부를 결정하세요

### 파일을 한 번 더 확인하고 싶다면: SHA-256

PowerShell에서 다음 명령을 실행합니다.

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

그 결과를 Release ZIP 안의:

`CC69_Threads_Manager.exe.sha256`

값과 비교하세요. 두 값이 같다면 현재 보유한 EXE가 해당 Release에서 배포된 파일과 동일하다는 뜻입니다.

### SmartScreen과 실제 백신 탐지는 다릅니다

Windows Defender 또는 다른 백신 프로그램이 SmartScreen과 별도로 **구체적인 악성코드 이름, Trojan, Malware, PUA 등의 실제 탐지 결과**를 표시한다면 단순한 “알 수 없는 게시자” 경고와는 다른 상황입니다. 이 경우에는 경고를 무시하지 말고 배포 출처와 파일을 별도로 확인하세요.

**CC69는 이 프로젝트의 공식 GitHub Releases에서만 다운로드하는 것을 권장합니다.**

## 🔐 로그인 및 개인정보

Threads / Meta 비밀번호는 공식 로그인 페이지에서 입력합니다. CC69 자체 화면에 비밀번호를 입력하는 방식이 아닙니다.

## 🔎 빠른 검사가 불완전한 경우

Threads Web은 동적 로딩과 가상 목록을 사용합니다. 불완전하면 **전체 데이터 검사**로 전환하고 Meta / Threads 공식 다운로드 관계 데이터를 가져오세요.

## ⏳ 언팔로우 처리 시간

CC69는 계정을 하나씩 열고 확인하기 때문에 선택한 계정이 많을수록 시간이 오래 걸립니다. 시작 후 진행률을 확인하며 기다려 주세요.

## ⚠️ 사용 안내

Threads에서 인증, 제한, '나중에 다시 시도' 메시지가 나타나면 작업을 중지하고 나중에 다시 시도하세요.