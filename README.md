# 오늘 계획 플래너 (Simple Day Planner) 📅

**오늘 계획 플래너**는 하루를 3~5개의 핵심 작업으로만 채워 집중력을 극대화할 수 있도록 돕는 미니멀한 웹 기반 플래너입니다.

[GitHub Repository](https://github.com/s38827550-sys/simple-planner-test)

---

## 주요 기능 (Key Features)

### 1. 🎯 집중 관리 (Focus-based Planning)
- 하루에 꼭 해야 할 3~5가지의 핵심 작업을 추가하고 관리합니다.
- 작업별 시작 및 종료 시간을 설정하여 일일 타임라인을 한눈에 파악할 수 있습니다.

### 2. 🌓 테마 모드 (Dark/Light Mode)
- 사용자 선호도에 따라 다크 모드와 화이트 모드를 자유롭게 전환할 수 있습니다.
- 설정된 테마는 브라우저의 `localStorage`를 통해 새로고침 후에도 유지됩니다.

### 3. 📬 제휴 및 서비스 문의 (Partnership Form)
- **Formspree**를 연동하여 별도의 백엔드 서버 없이 사용자로부터 직접 이메일 문의를 받을 수 있습니다.

### 4. 💬 소셜 댓글 시스템 (Disqus Integration)
- **Disqus**를 통합하여 사용자들 간의 피드백과 의견 공유가 가능합니다.

### 5. 💾 데이터 로컬 저장
- 모든 계획 데이터는 브라우저 내부에 저장되어, 페이지를 닫아도 데이터가 사라지지 않습니다.

---

## 기술 스택 (Tech Stack)

- **Frontend:** HTML5, CSS3 (Vanilla CSS), JavaScript (Vanilla JS)
- **Backend-less Integration:** 
  - [Formspree](https://formspree.io/) (Contact Form)
  - [Disqus](https://disqus.com/) (Comments)

---

## 시작하기 (Getting Started)

이 프로젝트는 별도의 빌드 과정이 필요 없는 정적 HTML 파일입니다.

1. 이 저장소를 클론합니다:
   ```bash
   git clone https://github.com/s38827550-sys/simple-planner-test.git
   ```
2. `index.html` 파일을 브라우저에서 엽니다.

### 개인 설정 (Customization)
- **문의 폼:** `index.html` 내의 Formspree action URL을 본인의 ID로 변경하세요.
- **댓글:** `index.html` 내의 Disqus shortname(`simpleplannertest`)을 본인의 설정값으로 변경하세요.

---

## 라이선스 (License)

이 프로젝트는 자유롭게 수정 및 배포가 가능합니다.
