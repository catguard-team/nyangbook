# nyangbook

> 냥북 — 라즈베리파이 기반 자경단 보급 디바이스

**한 줄 요약**: 어르신·새끼고양이가 인터넷·문서·코딩 첫발 떼는 데 필요한 최소한의 "내 컴퓨터".

**철학**: 새 부품 사기 전에 동네에 굴러다니는 부품부터 활용. 못 구할 때만 신품. 빠른 게 아니라 **충분한 것**을 만든다.

---

## 문서

| 파일 | 무엇 |
|------|------|
| [`BOM.md`](./BOM.md) | v1 부품 리스트 + 단가 분석 + 시나리오별 대안 |
| `setup.sh` (예정) | OS 이미지 굽기 + 한국어 환경 + 기본 앱 자동 설치 스크립트 |
| `kiosk-mode.md` (예정) | 노묘용 큰 글씨·단순 메뉴 모드 가이드 |

---

## v1 목표 사양

- **CPU**: Raspberry Pi 5 (4GB 또는 8GB)
- **OS**: Raspberry Pi OS (Debian 기반, 64bit)
- **언어**: 한국어 기본 환경 (입력기 ibus + 나눔고딕)
- **기본 앱**: 크롬, LibreOffice, VS Code, 줌
- **네트워크**: 유선·Wi-Fi 둘 다
- **대상**: 어르신·어린이·자영업자

자세한 BOM은 [`BOM.md`](./BOM.md).

---

## 누가 쓰는가

| 시나리오 | 구성 |
|----------|------|
| 어르신용 (노묘) | 큰 모니터 + 큰 키보드 + 단순 데스크톱 + 카카오톡 PC |
| 어린이용 | 모니터 + 키보드 + Scratch + Tinkercad |
| 자영업자용 | 듀얼 모니터 + LibreOffice + 매장 관리 웹앱 |

각 시나리오별 자동 설정은 [`saenoyangi-handbook`](https://github.com/catguard-team/saenoyangi-handbook) 트랙과 연동.

---

## 기여

부품 가격 변동·새 모델 출시·국내 유통처 정보는 [`BOM.md`](./BOM.md) PR 환영. 가격은 **국내 일반 유통가 (쿠팡/네이버/디바이스마트)** 기준.

---

## 🧭 자경단 문서 지도

모든 자경단 문서 한눈에: [`.github/DOCS-MAP.md`](https://github.com/catguard-team/.github/blob/main/DOCS-MAP.md)

관련 레포:
- 📡 이 레포 (`nyangbook`) — 하드웨어 보급
- 🐾 [`saenoyangi-handbook`](https://github.com/catguard-team/saenoyangi-handbook) — 낥북으로 학습하는 트랙들
- 🍯 [`kkulzam-spot/linux/`](https://github.com/catguard-team/kkulzam-spot) — 라즈베리파이 꿀팁

---

<div align="center">
  <sub>동네에 굴러다니는 부품부터 · <strong>냐-옥.</strong></sub>
</div>
