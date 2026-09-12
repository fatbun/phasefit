<p align="center">
  <img src="./assets/logo.png" alt="PhaseFit" width="120" />
</p>
<h1 align="center">PhaseFit</h1>
<p align="center"><strong>AI 기반 영양 & 피트니스 트래킹으로 체계적인 바디 리컴포지션을.</strong></p>
<p align="center">사진으로 식단 기록. 대화형 운동 관리. 스마트 점수 시스템.<br>감량, 증량, 유지 -- 어떤 단계에서든 PhaseFit이 AI 파트너로 함께합니다.</p>
<p align="center">
  <a href="https://phasefit.top/ko/landing">공식 사이트</a> &nbsp;|&nbsp;
  <a href="https://phasefit.top/ko/pricing">요금제</a> &nbsp;|&nbsp;
  <a href="README.md">English</a> &nbsp;|&nbsp;
  <a href="README.zh-CN.md">中文</a> &nbsp;|&nbsp;
  <a href="README.ja-JP.md">日本語</a>
</p>

---

## PhaseFit이란?

PhaseFit은 AI를 활용하여 영양과 운동을 관리하는 단계별 체중 관리 앱입니다. 직접 칼로리를 계산할 필요 없이, 식사를 촬영하면 즉시 영양 분석을 받을 수 있고, 운동 내용도 자연스러운 한국어로 설명하면 자동으로 분석됩니다.

### 주요 기능

| 기능 | Free | Pro |
|---|---|---|
| 일일 AI 이용 횟수 | 5회 | 30회 |
| 식단 사진 인식 | 지원 | 지원 (고정밀 모델) |
| 영양 분석 | 기본 | 전체 |
| 식단 & 운동 기록 | 지원 | 지원 |
| 현지 식문화 맞춤 AI 인식 | 지원 | 지원 |
| 식단 & 운동 간편 복제 | 지원 | 지원 |
| 건강 체중 범위 | 지원 | 지원 |
| AI 모델 팩 선택 | -- | GLM5.2 Mix / DeepSeek V4 Pro Mix |
| 주간 영양 리포트 & 인사이트 | -- | 지원 |
| 우선 지원 | -- | 지원 |

신규 사용자는 **14일간 Pro 무료 체험**을 이용할 수 있습니다 (신용카드 불필요).

### 기술 스택

- **프론트엔드**: Vue 3 + Vite + TailwindCSS + ECharts
- **백엔드**: FastAPI + SQLAlchemy (async) + PostgreSQL
- **AI**: 멀티 프로바이더 OpenAI 호환 API
- **결제**: Creem (Visa, Mastercard, PayPal, Apple Pay, Google Pay)

### 다국어 지원

| 언어 | 상태 |
|---|---|
| English (en-US) | 지원 |
| 中文 (zh-CN) | 지원 |
| 日本語 (ja-JP) | 지원 |
| 한국어 (ko-KR) | 지원 |
| Spanish (es) | 출시 예정 |
| Portuguese (pt) | 출시 예정 |

지원 언어는 UI 번역뿐만 아니라, 각 지역의 식문화와 영양 데이터베이스에 최적화된 AI 프롬프트를 포함한 완전한 현지화를 제공합니다.

---

## 요금제

| 플랜 | 월간 | 연간 |
|---|---|---|
| Free | $0 | $0 |
| Pro | ~~$9.9~~ **$6.9**/월 | ~~$69~~ **$49**/년 (41% 할인) |

자세한 내용은 [요금 페이지](https://phasefit.top/ko/pricing)를 참고하세요.

---

## 피드백 & 버그 신고

버그를 발견했거나 기능 요청이 있으시면 [Issue를 생성](https://github.com/fatbun/phasefit/issues/new/choose)해 주세요.

직접 문의: [support@phasefit.top](mailto:support@phasefit.top)

---

## 링크

- [공식 사이트](https://phasefit.top/ko/landing)
- [개인정보처리방침](https://phasefit.top/ko/privacy)
- [이용약관](https://phasefit.top/ko/terms)

---

## 라이선스

본 리포지토리는 제품 문서와 이슈 트래킹만 포함합니다. PhaseFit 애플리케이션 소스 코드는 비공개입니다.

Copyright 2024-2026 PhaseFit. All rights reserved.
