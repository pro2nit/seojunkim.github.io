# Seojun Kim Personal Page

GitHub Pages에 바로 올릴 수 있는 정적 개인 페이지입니다. 참고 사이트처럼 좌측 프로필과 우측 본문 구조를 사용했고, 첨부 Notion export와 Google Scholar 공개 정보를 기반으로 구성했습니다.

## 미리보기

브라우저에서 `index.html`을 직접 열어도 동작합니다.

```bash
open index.html
```

로컬 서버로 확인하려면 다음 명령을 실행하세요.

```bash
python3 -m http.server 8000
```

그 다음 `http://localhost:8000`에서 확인할 수 있습니다.

현재 작업 폴더에서 Homebrew Python 서버가 멈추면 아래 명령을 사용하세요.

```bash
../.venv/bin/python -m http.server 8000 --bind 127.0.0.1
```

## GitHub Pages 배포

1. GitHub에서 `pro2nit.github.io` 저장소를 만듭니다.
2. 이 `personal-page/` 폴더 안의 파일을 저장소 루트로 옮깁니다.
3. `main` 브랜치에 커밋하고 push합니다.
4. GitHub 저장소의 `Settings > Pages`에서 `Deploy from a branch`, `main`, `/root`를 선택합니다.

## 공개 전 확인

첨부 원본에는 전화번호와 상세 주소가 있었지만, 공개 페이지에는 넣지 않았습니다. 필요하면 `index.html`의 프로필 영역에 직접 추가할 수 있습니다.

Google Scholar의 citation 수치는 정적 텍스트라서 시간이 지나면 수동으로 업데이트해야 합니다.
