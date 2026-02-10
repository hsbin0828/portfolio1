# 개인 포트폴리오 웹사이트

HTML, CSS, JavaScript로 제작된 개인 포트폴리오 웹사이트입니다.

## 📁 프로젝트 구조

```
├── index.html      # 메인 HTML
├── css/
│   └── style.css   # 스타일시트
├── js/
│   └── main.js     # JavaScript
└── README.md       # 설명서
```

## 🚀 로컬에서 실행하기

1. 프로젝트 폴더에서 `index.html` 파일을 브라우저로 열기
2. 또는 Live Server 같은 확장 프로그램 사용 (VS Code)

## 🌐 실제 URL로 배포하기

이 웹사이트는 정적 사이트이므로 아래 무료 서비스로 쉽게 배포할 수 있습니다.

### 방법 1: GitHub Pages (추천)

1. [GitHub](https://github.com)에 계정 생성
2. 새 저장소(Repository) 만들기
3. 프로젝트 파일들을 저장소에 업로드
4. 저장소 **Settings** → **Pages** → Source를 **main** 브랜치로 설정
5. 배포 완료 후 `https://[사용자명].github.io/[저장소명]` 으로 접속

### 방법 2: Netlify

1. [Netlify](https://www.netlify.com) 가입
2. "Add new site" → "Deploy manually" 선택
3. 프로젝트 폴더 전체를 드래그앤드롭
4. 자동으로 `https://[랜덤이름].netlify.app` URL 생성
5. 사이트 설정에서 커스텀 도메인 변경 가능

### 방법 3: Vercel

1. [Vercel](https://vercel.com) 가입
2. "Add New Project" → "Import" 선택
3. GitHub 저장소 연결 또는 폴더 업로드
4. 배포 후 `https://[프로젝트명].vercel.app` URL 제공

## ✏️ 내용 수정하기

- **index.html**: 소개, 프로젝트, 연락처 정보 수정
- **css/style.css**: `:root` 변수에서 색상·폰트 변경
- **js/main.js**: 추가 인터랙션 구현

## 📱 기능

- 반응형 디자인 (모바일/태블릿/데스크톱)
- 다크 테마 UI
- 스크롤 애니메이션
- 숫자 카운터 애니메이션
- 스킬 바 프로그레스 애니메이션
- 모바일 햄버거 메뉴
