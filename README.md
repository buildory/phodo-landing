# PhoDo Landing Page

## 로컬 테스트 방법

로컬에서 테스트하려면 HTTP 서버가 필요합니다.

### Python을 사용하는 경우:
```bash
# Python 3
python -m http.server 8000

# 그 다음 브라우저에서 http://localhost:8000 접속
```

### Node.js를 사용하는 경우:
```bash
npx http-server -p 8000

# 그 다음 브라우저에서 http://localhost:8000 접속
```

### VS Code를 사용하는 경우:
- Live Server 확장 프로그램 설치 후 사용

## 페이지 구조

- `/` 또는 `index.html` → 메인 페이지 (phodo.net)
- `/phodo-test/` 또는 `phodo-test/index.html` → 포도테스트 페이지 (phodo.net/phodo-test)

## GitHub Pages 배포

이 저장소를 GitHub Pages로 배포하면:
- `phodo.net` → 메인 페이지
- `phodo.net/phodo-test` → 포도테스트 페이지

자동으로 작동합니다.

