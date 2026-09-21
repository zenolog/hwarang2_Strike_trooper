# STRIKE TROOPER · HWARANG

스마트폰 가로 화면에 맞춘 2라인 액션 슈팅 게임입니다. 별도의 빌드 과정 없이 정적 웹사이트로 실행됩니다.

## 로컬 실행

`dist/index.html`을 직접 열거나 로컬 웹 서버의 루트 디렉터리를 `dist`로 지정합니다.

```bash
python -m http.server 8080 --directory dist
```

브라우저에서 `http://localhost:8080`을 열면 됩니다.

## GitHub Pages 배포

1. 이 저장소를 GitHub의 `main` 브랜치에 업로드합니다.
2. 저장소의 **Settings → Pages**로 이동합니다.
3. **Build and deployment → Source**를 **GitHub Actions**로 설정합니다.
4. `main` 브랜치에 변경사항을 올리면 포함된 워크플로가 `dist` 폴더를 자동 배포합니다.

모든 이미지와 음원은 상대 경로를 사용하므로 GitHub Pages의 프로젝트 주소에서도 동작합니다.
