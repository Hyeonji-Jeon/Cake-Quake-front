# Cake-Quake-front
<hr>
> AI 추천과 발주 기능을 갖춘 맞춤형 레터링 케이크 예약 플랫폼
> React 기반 **Frontend 레파지토리**

---

## 📌 프로젝트 개요
CakeQuake는 구매자와 판매자가 소통하며 맞춤형 케이크를 주문·판매할 수 있도록 지원하는 서비스입니다.  
본 레포지토리는 **프론트엔드(React)** 구현을 담당하며, UI/UX 구현, 사용자 인터페이스 제공합니다.

---

## 🛠️ 기술 스택
- **Language**: JavaScript (ES6+)  
- **Framework / Library**: React, Zustand, Tailwind CSS, React Router, Axios, Framer Motion  
- **Build Tool / Bundler**: Vite  
- **Infra**: AWS S3 (이미지 저장)  
- **CI/CD**: GitHub Actions 

---


## 📖 주요 기능
- 🛒 **구매자**
  - 케이크 옵션 선택 및 주문 UI
  - AI 추천 디자인 표시
  - 알림 확인 및 실시간 알림 UI
  - 뱃지 & 온도 & 포인트 시스템 UI

- 🧑‍🍳 **판매자**
  - 상품 등록/수정/삭제 UI
  - 옵션 타입 및 값 관리 UI
  - 주문 내역 관리 화면
  - 총 판매량 그래프 화면

- 👨‍💻 **관리자**
  - 회원/발주 관리 화면
  - 신고 접수 및 제재 처리 UI

---

## ⚙️ 프로젝트 구조
```bash
📦 cake-quake-front
├─ public/
│  ├─ cakeImage/              # 케이크 기본 이미지
│  ├─ welcomeImages/          # 웰컴 화면 이미지
│  ├─ logo.png                # 로고 이미지
│  └─ shop_default_image.png  # 매장 기본 이미지
├─ src/
│  ├─ api/                    # API 호출 관련 함수
│  ├─ assets/                 # 정적 리소스 (폰트, 아이콘 등)
│  ├─ components/             # 컴포넌트
│  ├─ constants/              # 상수 정의
│  ├─ dto/                    # 데이터 전송 객체
│  ├─ hooks/                  # 커스텀 훅
│  ├─ layouts/                # 레이아웃
│  ├─ pages/                  # 페이지
│  ├─ router/                 # React Router 설정
│  ├─ store/                  # Zustand 상태 관리
│  ├─ utils/                  # 헬퍼 함수
│  ├─ App.css                 # 전역 스타일
│  ├─ App.jsx                 
│  ├─ index.css               # 추가 스타일
│  └─ main.jsx                
├─ env.                       # 환경 변수 관련 파일
├─ package-lock.json
├─ package.json
├─ tailwind.config.js
└─ vite.config.js  
```

---

## 🐞 트러블슈팅

문제: AI 응답 지연
→ 해결: 귀여운 로딩 스피너 구현

문제: 상품 썸네일 지정 오류
→ 해결: 선택된 썸네일 우선 로직 적용, React 상태 관리 개선

문제: 카카오 지도 API 연동 오류
→ 해결: 사용 가능한 카카오 앱키로 변경

---

## 👤 본인 역할
- **UI/UX 구현**
  - 웰컴 페이지 및 구매자 마이페이지
  - 주문 및 옵션 선택 화면
  - AI 추천 결과 표시
  - 지도 연동 및 실시간 알림
  - 뱃지 시스템 UI
  - 알림 시스템 UI
 
- **기능/인프라 구현**
  - AWS S3 이미지 업로드 (상품 이미지, 썸네일 관리)

- **기술/스타일링**
  - Tailwind CSS 활용 반응형 화면 설계
  - 전체적인 디자인 및 화면 레이아웃 담당

---

## 📅 개발 기간
2025.05.08 ~ 2025.07.11
