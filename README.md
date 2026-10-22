# dnSpyEx 6.6.0 — 비공식 한국어 패치 / Unofficial Korean Localization

> **비공식 프로젝트 / UNOFFICIAL PROJECT**
>
> 이 저장소의 한국어 번역 및 패치는 개인이 독립적으로 제공하는 비공식 작업물입니다. **dnSpyEx 공식 개발팀의 공식 배포판이나 공식 한국어 지원이 아닙니다.**  
> This is an independently maintained, **unofficial** Korean localization. It is **not** an official dnSpyEx release or officially endorsed translation.

- **기반 프로그램 / Based on:** [dnSpyEx](https://github.com/dnSpyEx/dnSpy), 6.6.0
- **한국어 번역 / Korean translator:** 꿈을꾸는 파랑새 (Sakai)
- **지원 대상 / Targets:** .NET 10 (`net10.0-windows`), .NET Framework 4.8 (`net48`)
- **상태 / Validation:** 사용자 환경에서 실행을 확인했으나, 프레임워크별 전체 기능·UI 잘림 등은 완전히 검증되지 않았습니다. / Execution was confirmed in a user environment, but full functionality and UI layout for each target have not been comprehensively verified.

## 🇰🇷 한국어 안내

### 배포 파일

| 대상 | 배포 ZIP 파일 | 크기 | SHA-256 |
| --- | --- | ---: | --- |
| .NET 10 / Windows | `dnSpyEx-Korean net10.0 windows.zip` | 4,314,500 bytes | `f2f2fbd5144db063bb9981810156277f3e2fbc641aa9bb084dd41f190d75c86d` |
| .NET Framework 4.8 | `dnSpyEx-Korean net48.zip` | 2,348,147 bytes | `bf89060a61f0c9e733abbce868800cdcfd0947d7b641120e4b35209fee7a8ebb` |

**참고:** 위 ZIP의 해시는 전달된 실제 압축파일을 기준으로 계산했습니다. ZIP 내부 파일별 SHA-256은 [FILE-HASHES.txt](FILE-HASHES.txt)에 기록했습니다. 저장소에 ZIP이 등록되기 전에는 ZIP 다운로드 링크가 제공되지 않습니다.

### 설치 방법

1. 현재 사용하는 dnSpyEx 버전 및 실행 대상이 .NET 10인지 .NET Framework 4.8인지 확인합니다.
2. **기존 설치 폴더를 먼저 백업**하고 dnSpyEx를 종료합니다.
3. 사용 중인 프레임워크와 일치하는 **ZIP 하나만** 압축 해제합니다.
4. 압축파일의 폴더 구조를 확인한 뒤 해당 파일들을 원본 dnSpyEx 배포판의 **동일한 상대 경로**에 적용합니다. `bin/ko-KR/` 폴더는 언어 리소스이며, 이 ZIP에는 일부 **프로그램 본체 DLL도 포함**되어 있습니다. 따라서 `ko-KR` 폴더만 복사하는 순수 언어 리소스 패키지와는 구별해야 합니다.
5. 프로그램을 실행해 한국어 표시와 주요 기능을 확인합니다. 문제가 발생하면 백업한 원본 파일로 복원합니다.

**주의:** 두 프레임워크용 파일을 섞어 사용하거나, 호환되지 않는 dnSpyEx 버전에 임의 적용하지 마십시오. ZIP에 포함된 `dnSpy.exe` 또는 본체 DLL은 기존 파일을 덮어쓸 수 있습니다.

### 검증 및 문제 보고

Windows PowerShell에서 다운로드한 파일의 해시를 확인할 수 있습니다.

```powershell
Get-FileHash -Algorithm SHA256 '.\dnSpyEx-Korean net10.0 windows.zip'
Get-FileHash -Algorithm SHA256 '.\dnSpyEx-Korean net48.zip'
```

실행 확인은 전체 기능 테스트나 보안 검증 완료를 의미하지 않습니다.
### 연구 및 번역 활동 후원

### 💖 Sponsor this project | 프로젝트 후원

이 비공식 한국어화 작업과 독립 보안 연구가 도움이 되셨다면 자발적으로 후원하실 수 있습니다. 번역 파일과 분석 자료는 후원 여부에 관계없이 공개됩니다.

<table>
  <tr>
    <td align="center" width="50%">
      <strong>☕ Ko-fi · 온라인 후원</strong><br><br>
      <a href="https://ko-fi.com/sakai38666">
        <img src="https://raw.githubusercontent.com/M26Pershing90mm/M26Pershing90mm/main/%EB%B0%A4%EC%9D%98%20%EC%9C%84%ED%98%91%20%EB%B6%84%EC%84%9D%EC%8B%A4.png" width="320" alt="밤의 위협 분석실 — 독립 보안 연구 및 한국어 현지화 후원 이미지">
      </a><br><br>
      <a href="https://ko-fi.com/sakai38666">
        <img src="https://img.shields.io/badge/Sponsor_on-Ko--fi-FF5E5B?style=for-the-badge&logo=kofi&logoColor=white" alt="Support this unofficial localization on Ko-fi">
      </a><br><br>
      <a href="https://ko-fi.com/sakai38666">Ko-fi 후원 페이지 열기 / Support on Ko-fi</a>
    </td>
    <td align="center" width="50%">
      <strong>🇰🇷 카카오페이 · KakaoPay QR</strong><br><br>
      <img src="https://raw.githubusercontent.com/M26Pershing90mm/M26Pershing90mm/main/kakaopay-qr.png" width="205" alt="카카오페이 후원 QR 코드 / KakaoPay donation QR code"><br><br>
      <sub>카카오톡 또는 카카오페이 앱으로 QR을 스캔하세요.<br>Scan with KakaoTalk or KakaoPay.</sub>
    </td>
  </tr>
</table>

> Ko-fi 버튼은 **Ko-fi 후원 페이지**로 이동하며, 카카오페이 QR은 **카카오페이 앱에서 스캔하는 별도의 후원 수단**입니다. 이 프로젝트는 dnSpyEx 공식 개발팀과 무관한 비공식 한국어화 프로젝트입니다.

- [후원 안내 / Support information](https://wezard4u.tistory.com/6259)
- [번역자 프로필 / Translator's profile](https://github.com/M26Pershing90mm)

보안 분석·독립 연구·오픈소스 한국어 현지화 작업에 대한 후원은 **전적으로 자발적**입니다. 후원 없이도 자료를 읽고 공유하는 것만으로 도움이 됩니다.

- [후원 안내 (한국어) — 꿈을꾸는 파랑새](https://wezard4u.tistory.com/6259)
- [Ko-fi — sakai38666](https://ko-fi.com/sakai38666)
- [GitHub 프로필 — M26Pershing90mm](https://github.com/M26Pershing90mm)

---

## 🇺🇸 English

This repository documents an **unofficial** Korean localization for dnSpyEx 6.6.0, translated by **꿈을꾸는 파랑새 (Sakai)**. It is independently maintained and is not affiliated with, endorsed by, or an official release of the dnSpyEx development team.

Two different build targets are provided: **.NET 10 / Windows** and **.NET Framework 4.8**. Choose **only** the ZIP matching your existing installation. Back up the installation directory, close dnSpyEx, and extract files to the corresponding relative paths. These packages contain both Korean `ko-KR` satellite assemblies and selected application binaries; **they are not resource-only patches**. Do not mix files from the two targets.

The archive names, sizes, and SHA-256 values are listed in the table above. File-level hashes are documented in [FILE-HASHES.txt](FILE-HASHES.txt). Successful launch in one user environment does **not** constitute complete compatibility, functional, security, or user-interface certification.

If this volunteer localization or the security research is useful, support is optional:

- [Support information](https://wezard4u.tistory.com/6259)
- [Ko-fi](https://ko-fi.com/sakai38666)

## Licensing / 라이선스

### 🇰🇷 한국어

이 저장소는 **dnSpyEx 6.6.0 비공식 한국어화 프로젝트**이며, dnSpyEx 공식 개발팀에서 제작하거나 승인한 공식 번역본이 아닙니다.

- **dnSpyEx 원본 프로그램과 타사 구성요소**의 저작권은 각각의 원저작권자에게 있으며, 해당 구성요소에 적용되는 원래 라이선스를 따릅니다.
- 이 저장소의 [LICENSE](LICENSE) 파일에는 **GNU General Public License 버전 3(GPL-3.0)** 전문이 수록되어 있습니다. 구성요소마다 적용 조건이 다를 수 있으므로, 배포·수정·재사용 시 각 원본 프로젝트의 라이선스와 고지 사항을 함께 확인해야 합니다.
- **한국어 번역 및 현지화 기여자:** 꿈을꾸는 파랑새(Sakai). 이 표기는 원본 소프트웨어에 대한 소유권이나 공식 개발팀과의 관계를 의미하지 않습니다.
- 파일을 재배포하거나 수정할 경우 해당 원본 라이선스에서 요구하는 저작권 표시, 라이선스 고지, 소스 코드 제공 등의 의무가 적용될 수 있습니다.

### 🇺🇸 English

This repository provides an **unofficial Korean localization for dnSpyEx 6.6.0**. It is not an official translation produced or endorsed by the dnSpyEx development team.

- **dnSpyEx and third-party components** remain the property of their respective copyright holders and are governed by their applicable original licenses.
- The [LICENSE](LICENSE) file included in this repository contains the text of the **GNU General Public License version 3 (GPL-3.0)**. Different components may have different licensing terms; check the relevant upstream licenses and notices before redistributing, modifying, or reusing any files.
- **Korean translation and localization contributor:** 꿈을꾸는 파랑새 (Sakai). This credit does not imply ownership of the original software or an official affiliation with its developers.
- Redistribution or modification may require retaining copyright notices, including license information, and providing source code, as specified by the applicable upstream licenses.
