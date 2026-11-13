NEON FOUR v0.74.0 — 분리형 자산 패키지

index.html과 assets 폴더를 반드시 같은 위치에 유지하세요.

권장 실행: 이 폴더에서 로컬 웹 서버를 실행한 뒤 http://localhost:8000 으로 접속하세요.
예: Python이 설치된 PC에서 폴더를 연 뒤 `python -m http.server 8000` 실행.

파일:// 직접 열기는 브라우저 보안 정책에 따라 일부 외부 자산 로딩이 제한될 수 있습니다.
Netlify 배포 시 ZIP을 풀고 index.html과 assets 폴더를 함께 배포하세요.

모든 기존 data:...;base64 자산을 assets/extracted 안의 개별 파일로 분리했습니다.
