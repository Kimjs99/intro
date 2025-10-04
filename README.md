[README.md](https://github.com/user-attachments/files/22694090/README.md)
# 김민수 자기소개 페이지

> 사용자에게 가치 있는 서비스를 제공하는 소프트웨어 개발자

[![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white)](https://developer.mozilla.org/ko/docs/Web/HTML)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white)](https://developer.mozilla.org/ko/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black)](https://developer.mozilla.org/ko/docs/Web/JavaScript)
[![Responsive](https://img.shields.io/badge/Responsive-Design-00C4CC?style=flat-square)](https://web.dev/responsive-web-design-basics/)

## 📋 프로젝트 소개

Brittany Chiang의 포트폴리오 사이트를 참고하여 제작한 모던하고 반응형 자기소개 페이지입니다. 다크 테마와 미니멀한 디자인을 통해 전문적이고 매력적인 개인 브랜딩을 구현했습니다.

## ✨ 주요 특징

### 🎨 **디자인**
- **다크 테마**: 깊은 네이비(`#0a192f`) 배경에 밝은 텍스트
- **모던한 색상 팔레트**: 그린(`#64ffda`), 블루(`#57cbff`) 액센트 컬러
- **미니멀한 레이아웃**: 불필요한 요소 제거, 핵심 정보에 집중
- **Inter 폰트**: 깔끔하고 모던한 타이포그래피

### 🚀 **고급 기능**
- **부드러운 스크롤**: 섹션 간 자연스러운 전환
- **마우스 커서 효과**: 커스텀 커서와 호버 애니메이션
- **패럴랙스 효과**: 스크롤 시 요소들의 3D 움직임
- **타이핑 애니메이션**: 텍스트가 타이핑되는 효과
- **스크롤 진행률**: 상단에 스크롤 진행도 표시
- **탭 인터페이스**: 경험 섹션의 인터랙티브 탭

### 📱 **반응형 디자인**
- **모바일 최적화**: 햄버거 메뉴와 터치 친화적 인터페이스
- **유연한 그리드**: 모든 화면 크기에서 완벽한 레이아웃
- **적응형 타이포그래피**: 화면 크기에 따른 폰트 크기 조절

## 🛠️ 기술 스택

- **HTML5**: 시맨틱 마크업
- **CSS3**: 
  - CSS Grid & Flexbox
  - CSS Variables
  - CSS Animations & Transitions
  - Media Queries
- **JavaScript (ES6+)**:
  - Intersection Observer API
  - Smooth Scrolling
  - Event Delegation
  - Debouncing

## 📁 프로젝트 구조

```
htmlcssjs/
├── index.html          # 메인 HTML 파일
├── style.css           # CSS 스타일시트
├── script.js           # JavaScript 기능
├── P.png              # 프로필 이미지
├── 자기소개서 실습용.txt  # 원본 자기소개서
└── README.md          # 프로젝트 문서
```

## 🎯 섹션 구성

### 1. **Hero Section**
- 임팩트 있는 인트로와 프로필 이미지
- 타이핑 애니메이션 효과
- CTA 버튼 (프로젝트 보기, 연락하기)

### 2. **About Section**
- 개인 소개 및 기술 스택
- 프로필 이미지와 호버 오버레이 효과
- 기술 태그 애니메이션

### 3. **Experience Section**
- 탭으로 구성된 경험 섹션
- 해커톤 우수상 수상 경험
- 학회 멘토링 활동

### 4. **Work Section**
- 주요 프로젝트 포트폴리오
- 프로젝트 카드 3D 호버 효과
- 외부 링크 및 GitHub 링크

### 5. **Contact Section**
- 연락처 정보
- 생활신조 ("기술은 사람을 위해 존재한다")
- 클립보드 복사 기능

## 🚀 시작하기

### 설치 및 실행

1. **저장소 클론**
   ```bash
   git clone [repository-url]
   cd htmlcssjs
   ```

2. **브라우저에서 열기**
   ```bash
   # 방법 1: 파일 직접 열기
   open index.html
   
   # 방법 2: 로컬 서버 실행 (권장)
   python -m http.server 8000
   # 또는
   npx serve .
   ```

3. **브라우저에서 확인**
   - `http://localhost:8000` (로컬 서버 사용 시)
   - 또는 `index.html` 파일을 직접 브라우저에서 열기

## 📱 반응형 브레이크포인트

- **Desktop**: 1024px 이상
- **Tablet**: 768px - 1023px
- **Mobile**: 767px 이하

## 🎨 커스터마이징

### 색상 변경
CSS 변수를 수정하여 색상을 변경할 수 있습니다:

```css
:root {
    --dark-navy: #0a192f;      /* 배경색 */
    --green: #64ffda;          /* 액센트 컬러 1 */
    --blue: #57cbff;           /* 액센트 컬러 2 */
    --lightest-slate: #ccd6f6; /* 텍스트 색상 */
}
```

### 프로필 이미지 변경
`P.png` 파일을 원하는 이미지로 교체하세요.

### 내용 수정
`index.html` 파일에서 텍스트 내용을 수정할 수 있습니다.

## 🔧 성능 최적화

- **디바운스 함수**: 스크롤 이벤트 최적화
- **Intersection Observer**: 효율적인 애니메이션 트리거
- **CSS 변수**: 일관된 디자인 시스템
- **부드러운 전환**: 60fps 애니메이션

## 📄 라이선스

이 프로젝트는 개인 포트폴리오 목적으로 제작되었습니다.

## 📞 연락처

- **이메일**: kimminsoo@example.com
- **전화**: 010-1234-5678
- **GitHub**: [github.com/kimminsoo](https://github.com/kimminsoo)
- **LinkedIn**: [linkedin.com/in/kimminsoo](https://linkedin.com/in/kimminsoo)

---

**"기술은 사람을 위해 존재한다"** - 김민수
