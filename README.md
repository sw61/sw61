# 이상원 (Sangwon Lee)

개선을 수치로 확인하는 프론트엔드 개발자입니다.
기능을 만들고 끝내는 게 아니라, 계측하고 → 병목을 특정하고 → 개선 효과를 숫자로 검증하는 방식으로 일합니다.

📮 dalka330@gmail.com

## 주요 프로젝트

### 🍶 술닥술닥 — 술 모임 서비스 (운영 중, private)

Next.js 웹/어드민 담당. 레포는 비공개라 코드 대신 결과로 소개합니다.

- 신규 유입 프로모션 게임에서 부정 참여 차단(캡차, URL 직접 접근 차단, 단계 검증)과 GA 퍼널 계측(커스텀 이벤트 8종) 전담
- 퍼널 분석으로 랜딩 이탈률 70.5% → 54.8%, 진입→응모 전환율 4.9% → 11.2% 개선
- CRA 어드민(17페이지, 약 1만 라인)의 Next.js 16 마이그레이션 단독 담당 — 프로덕션 빌드 26s → 14s

### 🍚 [소소잇](https://github.com/sw61/sosoeat) — 1인 가구 공동식사·공동구매 모임 서비스

프론트 5인 팀에서 인증 도메인 전담. FSD 아키텍처 기반.

- BFF 프록시 인증 설계: httpOnly 쿠키 + 401 시 토큰 갱신 후 재시도, 동시 401에서도 갱신이 중복되지 않도록 진행 중인 Promise 공유
- Suspense 분리 + 폰트 서브셋 자체 호스팅으로 LCP 5.8s → 4.3s (Slow 4G, Lighthouse 5회 평균)
- Jest·Storybook 테스트 환경을 프로젝트 초기에 구축해 팀 표준으로 정착 (팀 전체 테스트 58파일, 스토리 43개)

### 📋 [체험콕 어드민](https://github.com/experience-kok/kok-web-admin) — 체험단 중개 서비스

어드민 프론트 단독 개발.

- TanStack Query 도입으로 중복 API 호출 4회 → 1회, 뮤테이션 후 화면 자동 동기화
- 테이블 4종의 필터·페이지·검색 상태를 URL 쿼리스트링과 동기화

## 기술 스택

`React` `Next.js` `TypeScript` `TanStack Query` `Zustand` `React Hook Form` `Zod` `Tailwind CSS` `Jest` `Storybook` `GitHub Actions`
