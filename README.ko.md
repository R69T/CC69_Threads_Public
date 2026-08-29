<p align="center"><a href="README.md">繁體中文</a> ｜ <a href="README.en.md">English</a> ｜ <a href="README.ja.md">日本語</a> ｜ <strong>한국어</strong></p>

# CC69 Threads Manager

**Threads 팔로우 관계를 확인하고 정리하는 Windows 데스크톱 앱입니다.**

[⬇️ 최신 버전 다운로드](https://github.com/R69T/CC69_Threads_Public/releases/latest) · [모든 릴리스](https://github.com/R69T/CC69_Threads_Public/releases)

## 주요 기능

- Followers / Following 빠른 검사
- 내가 팔로우하지만 상대가 나를 팔로우하지 않는 계정 찾기
- 상대는 나를 팔로우하지만 내가 아직 팔로우하지 않은 계정 찾기
- 맞팔 상태 표시
- 선택한 계정을 순서대로 언팔로우하고 진행률 표시
- 신규 팔로우 보호
- Meta / Threads 공식 다운로드 데이터를 가져와 더 완전한 비교
- 맞팔 센터 Beta
- 관계 데이터의 로컬 저장

빠른 검사는 **최근 24시간 기준 최대 6회**까지 사용할 수 있습니다.

## 언어

**繁體中文 / English / 日本語 / 한국어**를 내장합니다.

첫 실행 시 Windows 시스템 언어를 기준으로 UI 언어를 자동 선택합니다. 이후 앱 상단에서 언제든지 변경할 수 있으며 선택한 언어를 기억합니다.

## 다운로드 및 설치

최신 릴리스에서 다음 파일을 다운로드하세요.

`CC69_Threads_Manager_vX.X.X_Windows.zip`

그 다음:

1. ZIP 압축을 풉니다.
2. `CC69_Threads_Manager.exe`를 실행합니다.
3. 첫 실행에서 CC69가 필요한 로컬 데이터를 준비합니다.
4. 빠른 검사에서 Threads 로그인을 확인합니다.

ZIP에는 EXE, EXE SHA-256 파일, 간단한 README가 포함됩니다. Release 페이지에는 ZIP 자체의 SHA-256 파일도 제공됩니다.

## Windows SmartScreen / “알 수 없는 게시자” 안내

현재 CC69는 **상용 Windows 코드 서명 인증서로 EXE를 서명하지 않았습니다**.

그래서 Microsoft Defender SmartScreen에서 다음과 같은 메시지가 표시될 수 있습니다.

- “Windows의 PC 보호”
- “알 수 없는 게시자”
- 실행 전 확인 화면

**이 경고만으로 Windows가 바이러스를 탐지했다는 뜻은 아닙니다.** 주된 의미는 Windows가 확인할 수 있는 게시자 디지털 서명이나 충분한 앱 평판 정보가 없다는 것입니다.

하지만 출처를 알 수 없는 EXE는 실행하지 마세요. CC69는 반드시 공식 Releases에서 다운로드하세요:

https://github.com/R69T/CC69_Threads_Public/releases

PowerShell에서 SHA-256을 확인할 수 있습니다:

```powershell
Get-FileHash .\CC69_Threads_Manager.exe -Algorithm SHA256
```

ZIP에 포함된 `CC69_Threads_Manager.exe.sha256`과 비교하세요.

## 로그인 및 개인정보

로그인은 Threads / Meta 공식 페이지에서 진행합니다. CC69 인터페이스에 Threads / Meta 비밀번호를 입력할 필요가 없습니다.

로그인 후 “로그인 정보를 저장하시겠습니까?”와 같은 단계가 표시되면, CC69는 이후 브라우저 로그인 상태를 재사용할 수 있도록 해당 단계를 완료하려고 시도합니다.

## 빠른 검사 vs 전체 데이터 검사

### 빠른 검사

일상적인 확인에 적합합니다. Threads Web에서 가져올 수 있는 Followers / Following 정보를 읽고, 실제로 가져온 개수와 Threads가 표시하는 전체 개수를 비교합니다.

Threads는 동적 로딩과 가상 목록을 사용하므로 일부 계정에서는 결과가 불완전할 수 있습니다. CC69는 가져오지 못한 계정을 확인된 결과로 취급하지 않습니다.

### 다운로드 데이터 전체 검사

가장 완전한 Followers / Following 비교가 필요하면 Meta에서 본인의 Threads 데이터를 다운로드한 뒤 CC69로 가져오세요. 빠른 검사가 불완전할 때 권장되는 방법입니다.

## 맞팔 센터 Beta

참여는 자율입니다. CC69는 아직 매칭되지 않은 참여 계정을 배정하고 순서대로 처리할 수 있습니다. 이미 맞팔 상태인 계정은 팔로우 실패가 아니라 완료로 처리할 수 있습니다.

## 사용 시 주의사항

Threads의 페이지 구조와 플랫폼 제한은 변경될 수 있습니다. 인증 요청, 일시 제한, “나중에 다시 시도” 등의 메시지가 표시되면 작업을 중지하고 나중에 다시 사용하세요.

CC69는 특정 작업 빈도가 플랫폼 제한을 반드시 피할 수 있다고 보장하지 않습니다.
