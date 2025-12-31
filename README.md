# Gemini Canvas HTML 슬라이드 전체 화면 슬라이드 쇼 변환기

Gemini Canvas에서 작성한 HTML 슬라이드(슬라이드 부분만 추출한 HTML)를 입력하면, **“전체 화면으로 슬라이드 쇼”** 기능을 자동으로 추가한 뒤 수정된 HTML을 다운로드할 수 있게 해주는 단일 파일 웹 도구입니다.

- 드래그 앤 드롭 또는 파일 선택으로 원본 HTML을 자동으로 처리합니다.
- 변환은 **브라우저 로컬에서만** 수행되며, 입력 파일은 외부 서버로 전송되지 않습니다.
- 한국어/영어 UI 전환을 지원합니다.

---

## 예시(실행 방법)

### 1) GitHub Pages로 배포(권장)
1. 이 저장소 루트에 `index.html`을 둔 상태로 커밋/푸시합니다.
2. GitHub에서 **Settings → Pages**로 이동합니다.
3. **Build and deployment**에서 `Deploy from a branch`를 선택합니다.
4. Branch(예: `main`)와 폴더(보통 `/root`)를 선택하고 저장합니다.
5. 제공된 GitHub Pages 주소로 접속합니다.

참고 문서: GitHub Pages 공식 문서  
- https://docs.github.com/en/pages

### 2) 로컬에서 실행
빌드 과정이 필요 없습니다.

- `index.html`을 더블 클릭해 브라우저로 열거나,
- 간단한 로컬 서버로 실행합니다(예시):

```bash
# Python 3
python -m http.server 8000
