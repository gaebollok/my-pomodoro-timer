# Focus Flow - 포모도로 타이머

과학적으로 검증된 포모도로 기법 기반 무료 타이머

## 🎯 주요 기능

### ⏱️ 타이머 모드
- **포모도로**: 여유/일반/집중 모드
- **운동**: HIIT 초급/중급/고급, Tabata
- **명상**: 잡생각 정리, 심호흡, 짧은/긴 명상
- **Custom**: 사용자 정의 설정

### 🎨 디자인
- 5가지 테마 (Deep Focus, Forest Calm, Twilight, Warm Sepia, Ocean Deep)
- 깔끔한 미니멀 UI
- 반응형 디자인 (모바일/데스크톱)

### 🌐 다국어 지원
- 한국어 / English 전환

### 🎵 배경음
- YouTube 재생목록 연동 (사용자 커스텀)

### 💾 데이터 관리
- 로컬 저장소 자동 저장
- 설정 내보내기/불러오기 (코드 방식)

## 🚀 사용 방법

1. `index.html` 파일을 브라우저에서 열기
2. 원하는 모드 선택 (포모도로/운동/명상/Custom)
3. 타이머 클릭으로 시작/일시정지
4. 스페이스바로도 제어 가능

## 📁 파일 구조

```
focus-timer/
├── index.html          # 메인 파일 (모든 코드 포함)
├── sounds/             # 알림음 폴더 (현재 Web Audio API 사용)
└── README.md
```

## 🌐 배포 방법

### GitHub Pages
1. GitHub 저장소 생성
2. 파일 업로드
3. Settings → Pages → 활성화
4. `https://username.github.io/focus-timer/` 접속

### Vercel
1. https://vercel.com 접속
2. 폴더를 드래그 앤 드롭
3. 자동 배포 완료

## 🎨 테마 색상

| 테마 | 배경색 | 강조색 |
|------|--------|--------|
| Deep Focus | #0f1117 | #4a9eff |
| Forest Calm | #152820 | #5fb584 |
| Twilight | #1a1625 | #b088f9 |
| Warm Sepia | #1c1915 | #d4a574 |
| Ocean Deep | #0f1821 | #3eb0c9 |

## ⚡ 최적화

- 단일 HTML 파일 (의존성 최소화)
- Tailwind CSS CDN (빠른 로딩)
- Web Audio API (내장 알림음)
- LocalStorage (설정 저장)

## 📊 SEO

- 시맨틱 HTML
- Open Graph 메타 태그
- 구조화된 데이터 (Schema.org)
- 모바일 최적화

## 🔧 기술 스택

- HTML5
- Tailwind CSS (CDN)
- Vanilla JavaScript (ES6+)
- Web Audio API
- YouTube Iframe API
- LocalStorage API

## 📝 라이선스

MIT License

## 👤 제작자

Focus Flow - 집중력 향상을 위한 도구

---

**버전**: 1.0  
**최종 업데이트**: 2026-02-08
