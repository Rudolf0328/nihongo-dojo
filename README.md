# 일본어 공부 SPA 애플리케이션

Vue 3 + Vite + Pinia를 사용한 일본어 학습 SPA 애플리케이션입니다.

## 🚀 기능

- **히라가나 학습**: 46개의 기본 히라가나 학습
- **가타카나 학습**: 46개의 기본 가타카나 학습
- **단어 퀴즈**: 일본어 단어의 한국어 뜻 맞추기
- **한자 연습**: 기본 한자 20개와 읽기, 의미 학습
- **학습 통계**: 총 문제 수, 정답 수, 정답률, 학습 시간 확인

## 🛠️ 기술 스택

- **Vue 3**: Composition API 사용
- **Vite**: 빠른 개발 서버 및 빌드 도구
- **Vue Router**: SPA 라우팅
- **Pinia**: 상태 관리
- **CSS3**: 반응형 디자인

## 📦 설치 및 실행

### 1. 의존성 설치

```bash
npm install
```

### 2. 개발 서버 실행

```bash
npm run dev
```

### 3. 프로덕션 빌드

```bash
npm run build
```

### 4. 빌드 결과 미리보기

```bash
npm run preview
```

## 📁 프로젝트 구조

```
src/
├── components/          # 재사용 가능한 컴포넌트
├── views/              # 페이지 컴포넌트
│   ├── HiraganaView.vue
│   ├── KatakanaView.vue
│   ├── QuizView.vue
│   ├── KanjiView.vue
│   └── StatsView.vue
├── stores/             # Pinia 스토어
│   └── useStudyStore.js
├── router/             # Vue Router 설정
│   └── index.js
├── App.vue             # 루트 컴포넌트
├── main.js             # 애플리케이션 진입점
└── style.css           # 전역 스타일
```

## 🎯 주요 특징

- **반응형 디자인**: 모바일과 데스크톱 모두 지원
- **상태 관리**: Pinia를 통한 중앙화된 상태 관리
- **라우팅**: Vue Router를 통한 SPA 네비게이션
- **컴포넌트 분리**: 재사용 가능한 컴포넌트 구조
- **타입스크립트 지원**: 향후 타입스크립트 마이그레이션 가능

## 🔧 개발 명령어

- `npm run dev`: 개발 서버 시작 (http://localhost:3000)
- `npm run build`: 프로덕션 빌드
- `npm run preview`: 빌드 결과 미리보기
- `npm run serve`: 정적 파일 서빙

## 📱 브라우저 지원

- Chrome (최신)
- Firefox (최신)
- Safari (최신)
- Edge (최신)
