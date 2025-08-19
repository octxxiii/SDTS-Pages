# 🚀 SAWS Simulator - SAWS Simulation Data Transfer System

<div align="center">

![SAWS Simulator](https://img.shields.io/badge/SAWS-Simulator-blue?style=for-the-badge&logo=rocket)
![Version](https://img.shields.io/badge/Version-v1.3-green?style=for-the-badge)
![Platform](https://img.shields.io/badge/Platform-Cross--Platform-orange?style=for-the-badge)
![License](https://img.shields.io/badge/License-MIT-yellow?style=for-the-badge)

**위성 방공경보체계 시뮬레이션 데이터 전송 시스템**

[📥 다운로드](https://octxxiii.github.io/SDTS-Pages) • [🐛 이슈 제보](mailto:kdyw123@gmail.com) • [💬 카카오톡 오픈채팅](https://open.kakao.com/o/gWjZ0qBh)

</div>

---

## 📋 목차

- [🎯 프로젝트 개요](#-프로젝트-개요)
- [✨ 주요 기능](#-주요-기능)
- [🖥️ 시스템 요구사항](#️-시스템-요구사항)
- [📦 다운로드 및 설치](#-다운로드-및-설치)
- [🚀 사용법](#-사용법)


- [🤝 기여하기](#-기여하기)
- [📄 라이선스](#-라이선스)
- [📞 문의 및 지원](#-문의-및-지원)

---

## 🎯 프로젝트 개요

**SAWS Simulator**는 한국형 방공경보체계(KAMD)의 훈련과 테스트를 위한 전문 시뮬레이션 도구입니다. 탄도·항공 궤적을 시뮬레이션하고 ICCS(Integrated Command and Control System) 포맷으로 UDP 패킷을 송출하여 SAWS(Satellite Air Defence Warning System)에 전달하는 PyQt6 기반 데스크탑 애플리케이션입니다.

### 🎖️ 주요 용도

- **KAMD 탄도탄 시뮬레이션**: 다양한 탄도 궤적 시나리오 생성
- **MCRC 항적 시뮬레이션**: 항공기 궤적 및 위협 시뮬레이션
- **신호세기 TCP 서버**: 통신 신호 품질 모니터링
- **훈련상황 방공경보**: 실제 훈련 환경과 유사한 시나리오 제공

---

## ✨ 주요 기능

### 🔥 핵심 시뮬레이션 기능

| 기능 | 설명 | 지원 버전 |
|------|------|-----------|
| **탄도 궤적 시뮬레이션** | 다양한 발사각, 속도, 고도에서의 탄도 궤적 계산 | v1.0+ |
| **항공기 궤적 시뮬레이션** | 비행 경로, 속도, 고도 변화 시뮬레이션 | v1.1+ |
| **ICCS 데이터 포맷** | 표준 방공경보체계 데이터 형식 지원 | v1.0+ |
| **UDP 패킷 송출** | 실시간 데이터 전송 및 네트워크 통신 | v1.0+ |
| **다중 시나리오** | 훈련용 시나리오 템플릿 및 커스터마이징 | v1.2+ |

### 🎨 사용자 인터페이스

- **직관적인 GUI**: PyQt6 기반의 현대적 사용자 인터페이스
- **실시간 모니터링**: 궤적 및 데이터 전송 상태 실시간 표시
- **다크/라이트 모드**: 사용자 선호도에 따른 테마 지원
- **반응형 디자인**: 다양한 화면 해상도에 최적화

### 🔧 고급 기능

- **멀티스레딩**: 성능 최적화를 위한 비동기 처리
- **로깅 시스템**: 상세한 이벤트 및 오류 로그 기록
- **설정 관리**: 사용자 설정 및 프로파일 저장/불러오기
- **플러그인 시스템**: 확장 가능한 모듈 아키텍처

---

## 🖥️ 시스템 요구사항

### 💻 최소 시스템 요구사항

| 구성 요소 | 최소 요구사항 | 권장 사항 |
|-----------|---------------|-----------|
| **운영체제** | Windows 10, macOS 10.15+, Ubuntu 18.04+ | Windows 11, macOS 12+, Ubuntu 22.04+ |
| **프로세서** | Intel Core i3 / AMD Ryzen 3 | Intel Core i5 / AMD Ryzen 5 |
| **메모리** | 4GB RAM | 8GB RAM 이상 |
| **저장공간** | 500MB 여유 공간 | 1GB 여유 공간 |
| **네트워크** | 100Mbps 이더넷 | 1Gbps 이더넷 |

### 🐍 Python 환경

- **Python**: 3.8 이상 (3.9+ 권장)
- **PyQt6**: 6.0.0 이상
- **NumPy**: 1.20.0 이상
- **SciPy**: 1.7.0 이상

---

## 📦 다운로드 및 설치

### 🚀 최신 버전 다운로드

<div align="center">

[🪟 Windows (x64/ARM64)](https://octxxiii.github.io/SDTS-Pages) | [🍎 macOS (Intel/Apple Silicon)](https://octxxiii.github.io/SDTS-Pages) | [🐧 Linux (x64/ARM64)](https://octxxiii.github.io/SDTS-Pages)

</div>

### 📋 설치 단계

#### Windows
1. 다운로드한 `.exe` 파일 실행
2. 설치 마법사 따라하기
3. 바탕화면 바로가기 확인
4. 프로그램 실행

#### macOS
1. 다운로드한 `.dmg` 파일 열기
2. 애플리케이션 폴더로 드래그 앤 드롭
3. 보안 설정에서 "확인되지 않은 개발자" 허용
4. 프로그램 실행

#### Linux
1. 다운로드한 실행 파일에 실행 권한 부여:
   ```bash
   chmod +x SAWS-DataTransfer-v1.3-linux-x64
   ```
2. 프로그램 실행:
   ```bash
   ./SAWS-DataTransfer-v1.3-linux-x64
   ```

### 🔄 이전 버전 다운로드

사용자 환경이나 호환성 요구사항에 따라 이전 버전이 필요할 수 있습니다. 아래에서 원하는 버전을 선택하여 다운로드하세요.

#### 📥 Windows 이전 버전

| 버전 | 아키텍처 | 파일 형식 | 다운로드 | 릴리즈 날짜 | 지원 상태 |
|------|----------|-----------|----------|-------------|-----------|
| **v1.2** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.2-windows-x64.exe) | 2025-07-15 | ✅ 안정 지원 |
| **v1.2** | ARM64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.2-windows-arm64.exe) | 2025-07-15 | ✅ 안정 지원 |
| **v1.2** | x64 | `.pkg` | [다운로드](dist/windows/SAWS-DataTransfer-v1.2-windows-x64.pkg) | 2025-07-15 | ✅ 안정 지원 |
| **v1.1.5** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.5-windows-x64.exe) | 2025-06-25 | ⚠️ 제한적 지원 |
| **v1.1.4** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.4-windows-x64.exe) | 2025-06-20 | ⚠️ 제한적 지원 |
| **v1.1.3** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.3-windows-x64.exe) | 2025-06-15 | ⚠️ 제한적 지원 |
| **v1.1.2** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.2-windows-x64.exe) | 2025-06-10 | ⚠️ 제한적 지원 |
| **v1.1.1** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.1-windows-x64.exe) | 2025-06-05 | ⚠️ 제한적 지원 |
| **v1.1.0** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.1.0-windows-x64.exe) | 2025-06-01 | ⚠️ 제한적 지원 |
| **v1.0.10** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.0.10-windows-x64.exe) | 2025-05-25 | ❌ 레거시 |
| **v1.0.9.5** | x64 | `.exe` | [다운로드](dist/windows/SAWS-DataTransfer-v1.0.9.5-windows-x64.exe) | 2025-05-20 | ❌ 레거시 |

#### 🍎 macOS 이전 버전

| 버전 | 아키텍처 | 파일 형식 | 다운로드 | 릴리즈 날짜 | 지원 상태 |
|------|----------|-----------|----------|-------------|-----------|
| **v1.2** | Intel (x64) | 실행파일 | [다운로드](dist/macos/SAWS-DataTransfer-v1.2-macos-x64) | 2025-07-15 | ✅ 안정 지원 |
| **v1.2** | Apple Silicon (ARM64) | 실행파일 | [다운로드](dist/macos/SAWS-DataTransfer-v1.2-macos-arm64) | 2025-07-15 | ✅ 안정 지원 |

#### 🐧 Linux 이전 버전

| 버전 | 아키텍처 | 파일 형식 | 다운로드 | 릴리즈 날짜 | 지원 상태 |
|------|----------|-----------|----------|-------------|-----------|
| **v1.2** | x64 | 실행파일 | [다운로드](dist/linux/SAWS-DataTransfer-v1.2-linux-x64) | 2025-07-15 | ✅ 안정 지원 |
| **v1.2** | ARM64 | 실행파일 | [다운로드](dist/linux/SAWS-DataTransfer-v1.2-linux-arm64) | 2025-07-15 | ✅ 안정 지원 |

#### 📋 버전별 주요 변경사항

| 버전 | 주요 개선사항 | 호환성 | 권장 사용자 |
|------|--------------|--------|-------------|
| **v1.3** | 🆕 다중 시나리오, 향상된 UI | Windows 10+, macOS 10.15+, Ubuntu 18.04+ | 🎯 모든 사용자 |
| **v1.2** | 🔧 안정성 개선, 버그 수정 | Windows 8+, macOS 10.14+, Ubuntu 16.04+ | 🏢 기업 환경 |
| **v1.1.x** | ✨ 항공기 궤적 시뮬레이션 추가 | Windows 7+, macOS 10.13+, Ubuntu 14.04+ | 🧪 테스트 환경 |
| **v1.0.x** | 🚀 기본 탄도 궤적 시뮬레이션 | Windows 7+, macOS 10.12+, Ubuntu 14.04+ | 📚 학습/연구용 |

#### ⚠️ 이전 버전 사용 시 주의사항

- **v1.1.x 이하**: 일부 최신 기능이 제한될 수 있습니다
- **v1.0.x**: 보안 업데이트가 적용되지 않았을 수 있습니다
- **레거시 버전**: 기술 지원이 제한적이며, 새로운 기능 사용이 불가능합니다
- **권장사항**: 가능하면 최신 안정 버전(v1.3) 사용을 권장합니다

---

## 🚀 사용법

### 🎯 기본 사용법

1. **프로그램 실행**
   - 바탕화면 바로가기 또는 시작 메뉴에서 실행
   - 초기 로딩 화면에서 시스템 상태 확인

2. **시나리오 선택**
   - 메인 화면에서 원하는 시나리오 유형 선택
   - 탄도 궤적, 항공기 궤적, 또는 복합 시나리오

3. **매개변수 설정**
   - 발사 위치, 각도, 속도 등 세부 매개변수 조정
   - 실시간 미리보기로 결과 확인

4. **시뮬레이션 실행**
   - "시작" 버튼 클릭으로 시뮬레이션 시작
   - 진행 상황 모니터링 및 데이터 전송 상태 확인



### 📊 모니터링 및 로그

- **실시간 상태**: 궤적, 속도, 고도 등 실시간 표시
- **데이터 로그**: 전송된 모든 데이터의 상세 기록
- **오류 로그**: 발생한 문제점 및 해결 방법 제시
- **성능 메트릭**: CPU, 메모리, 네트워크 사용량 모니터링

---



---



## 🤝 기여하기

### 🐛 버그 리포트

버그를 발견하셨다면 [이슈 트래커](https://github.com/octxxiii/SDTS2/issues)에 상세한 정보와 함께 등록해 주세요.

**버그 리포트에 포함할 정보:**
- 운영체제 및 버전
- SAWS Simulator 버전
- 재현 단계
- 예상 동작과 실제 동작
- 오류 메시지 (있다면)
- 스크린샷 (UI 관련 문제인 경우)

### 💡 기능 제안

새로운 기능이나 개선 사항을 제안하고 싶으시다면 [Discussion](https://github.com/octxxiii/SDTS2/discussions)에 의견을 남겨 주세요.

### 🔧 코드 기여

1. **Fork** 저장소
2. **Feature branch** 생성 (`git checkout -b feature/amazing-feature`)
3. **Commit** 변경사항 (`git commit -m 'Add amazing feature'`)
4. **Push** 브랜치 (`git push origin feature/amazing-feature`)
5. **Pull Request** 생성

### 📋 기여 가이드라인

- **코드 스타일**: PEP 8 준수
- **테스트**: 새로운 기능에 대한 테스트 코드 작성
- **문서화**: 코드 주석 및 README 업데이트
- **커밋 메시지**: 명확하고 설명적인 메시지 작성

---

## 📄 라이선스

이 프로젝트는 **MIT 라이선스** 하에 배포됩니다. 자세한 내용은 [LICENSE](LICENSE) 파일을 참조하세요.

```
MIT License

Copyright (c) 2025 SAWS Simulator Team

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

---

## 📞 문의 및 지원

### 🆘 기술 지원

- **📧 이메일**: kdyw123@gmail.com
- **💬 카카오톡**: [오픈채팅방 참여](https://open.kakao.com/o/gWjZ0qBh)
- **🐛 GitHub Issues**: [이슈 등록](https://github.com/octxxiii/SDTS2/issues)



---

## 🙏 감사의 말

이 프로젝트는 다음과 같은 오픈소스 프로젝트들의 도움을 받았습니다:

- [PyQt6](https://www.riverbankcomputing.com/software/pyqt/) - GUI 프레임워크
- [NumPy](https://numpy.org/) - 수치 계산 라이브러리
- [SciPy](https://scipy.org/) - 과학 계산 라이브러리
- [PyInstaller](https://pyinstaller.org/) - 실행 파일 패키징

---

<div align="center">

**SAWS Simulator** - 방공경보체계 훈련의 새로운 표준 🚀

[⭐ Star this project](https://github.com/octxxiii/SDTS2) • [📥 Download](https://octxxiii.github.io/SDTS-Pages) • [🤝 Contribute](https://github.com/octxxiii/SDTS2/blob/main/CONTRIBUTING.md)

*Made with ❤️ for the defense community*

</div>
