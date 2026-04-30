# Hourly
Save your inspiration every hourly.

## HTML 파일 바로 미리보기 (가장 빠름)
네, 가능합니다. `index.html`은 단일 파일이므로 브라우저에서 바로 열 수 있습니다.

- 방법 1: 파일 탐색기에서 `index.html` 더블클릭
- 방법 2: 브라우저 창에 `index.html` 파일을 드래그 앤 드롭
- 방법 3: 주소창에 `file:///.../Hourly/index.html` 입력

> 참고: 일부 브라우저 기능(예: 엄격한 보안 정책이 필요한 API)은 `file://` 환경에서 제한될 수 있습니다. 이 프로젝트의 현재 기능(localStorage 기반 메모 저장)은 일반적으로 바로 동작합니다.

## GitHub Pages로 바로 열기
이 프로젝트는 `index.html` 단일 파일로 동작합니다.

1. GitHub 저장소에서 **Settings → Pages** 로 이동합니다.
2. **Build and deployment** 에서 **Source: Deploy from a branch** 를 선택합니다.
3. Branch를 `main`(또는 배포 브랜치), folder를 `/ (root)` 로 선택하고 저장합니다.
4. 배포가 완료되면 `https://<username>.github.io/<repo>/` 주소에서 바로 확인할 수 있습니다.

## 로컬 미리보기
### 1) VS Code Live Server
- VS Code에서 프로젝트 폴더를 열고 `index.html` 우클릭 → **Open with Live Server**.

### 2) Python 내장 서버
```bash
python -m http.server 8000
```
브라우저에서 `http://localhost:8000` 을 열어 확인합니다.
