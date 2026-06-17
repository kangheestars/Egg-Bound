Egg Bound 웹게임 업로드용 패키지 v116 Icon Fix

이번 업데이트:
- 갤럭시 홈화면에서 아이콘이 흰 배경 안에 작게 보이던 문제를 줄이기 위해 아이콘을 다시 만들었습니다.
- 투명 여백 없는 icon-192.png / icon-512.png / apple-touch-icon.png를 추가했습니다.
- manifest.json의 아이콘 설정을 any/maskable로 분리했습니다.
- service-worker.js 캐시 이름을 egg-bound-v116-iconfix-upload-ready-1 로 갱신했습니다.
- 업데이트 뉴스는 최신 소식만 표시됩니다.

업로드 방법:
1. 이 ZIP을 압축 해제합니다.
2. GitHub 저장소에 기존 파일을 덮어쓰기 업로드합니다.
3. index.html, manifest.json, service-worker.js, icon-192.png, icon-512.png, apple-touch-icon.png가 root에 있어야 합니다.
4. Commit changes를 누릅니다.
5. 적용 후 홈화면 아이콘은 바로 안 바뀔 수 있습니다. 기존 홈화면 아이콘을 삭제하고, 링크를 다시 열어서 홈 화면에 추가하면 가장 확실합니다.

주의:
- 이미 홈화면에 추가된 아이콘은 Android 런처가 오래 캐시할 수 있습니다.
- 게임 저장은 사이트 데이터에 있으므로, 홈화면 아이콘만 삭제하는 것은 보통 저장을 지우지 않습니다.
- 그래도 안전하게 저장 코드 복사/백업 파일 저장을 먼저 해두면 좋습니다.
