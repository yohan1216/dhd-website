# DHD Consulting Website

DHD Consulting 웹사이트 - Loaning.ai 디자인 스타일을 적용한 HTML + CSS 프로젝트

## 기술 스택

- HTML5
- CSS3 (SCSS 소스 포함)
- Vanilla JavaScript

## 프로젝트 구조

```
Website/
├── index.html          # 메인 HTML 파일
├── styles/
│   ├── main.css       # 컴파일된 CSS
│   └── main.scss      # SCSS 소스 파일
├── scripts/
│   └── main.js        # JavaScript 기능
└── README.md
```

## 실행 방법

### 설치

처음 사용 시 필요한 패키지를 설치하세요:
```bash
npm install
```

### 개발 모드 (권장)

SCSS 파일을 자동으로 감시하고 변경 시 CSS로 자동 컴파일:
```bash
npm run dev
```

이 명령어는 SCSS 파일이 변경될 때마다 자동으로 CSS를 재생성합니다.

### 웹 서버 실행

다른 터미널에서 웹 서버를 실행하세요:
```bash
npm run serve
# 또는
python3 -m http.server 8000
```

그 후 브라우저에서 `http://localhost:8000`으로 접속하세요.

### 개발 + 서버 동시 실행

SCSS 감시와 웹 서버를 동시에 실행:
```bash
npm start
```

### 프로덕션 빌드

압축된 CSS 파일 생성:
```bash
npm run build
```

확장된(readable) CSS 파일 생성:
```bash
npm run build:expanded
```

## 주요 기능

- 📱 **반응형 디자인**: 모바일, 태블릿, 데스크톱 모두 지원
- 🎨 **모던한 UI**: Loaning.ai 스타일의 깔끔한 디자인
- 🚀 **부드러운 애니메이션**: 호버 효과 및 스크롤 애니메이션
- 📱 **모바일 메뉴**: 햄버거 메뉴로 모바일 네비게이션 지원
- ❓ **FAQ 아코디언**: 인터랙티브한 FAQ 섹션
- 🔗 **부드러운 스크롤**: 앵커 링크 클릭 시 스무스 스크롤

## 섹션 구성

1. **Hero Section** - 메인 타이틀 및 CTA
2. **Trusted By** - 클라이언트 로고
3. **Pain Points** - 고객 문제 해결 방안
4. **Services** - 서비스 소개 (탭 기능)
5. **Job Seekers** - 구직자를 위한 섹션
6. **How It Works** - 프로세스 타임라인
7. **About** - DHD 스토리
8. **Testimonials** - 고객 후기
9. **Success Stories** - 성공 사례
10. **Industries** - 산업 전문성
11. **FAQ** - 자주 묻는 질문
12. **CTA** - 최종 행동 유도
13. **Footer** - 푸터 정보

## 커스터마이징

### 색상 변경

`styles/main.scss` 또는 `styles/main.css` 파일에서 색상 변수를 수정하세요:

```scss
$primary-color: #0ea5e9;  // 메인 브랜드 컬러
$primary-dark: #0284c7;   // 어두운 버전
$primary-light: #38bdf8;  // 밝은 버전
```

### 콘텐츠 변경

`index.html` 파일에서 직접 텍스트와 이미지를 수정하세요.

## 브라우저 지원

- Chrome (최신 버전)
- Firefox (최신 버전)
- Safari (최신 버전)
- Edge (최신 버전)

## 라이선스

© 2025 DHD Consulting. All rights reserved.
