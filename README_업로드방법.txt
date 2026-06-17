Egg Bound 웹게임 업로드용 패키지 v114

이 폴더 안 파일을 그대로 웹호스팅에 올리면 됩니다.

필수 파일:
- index.html
- manifest.json
- service-worker.js
- icon-192.png
- icon-512.png

가장 쉬운 업로드 방법:
1. GitHub 새 저장소 생성
2. 이 ZIP 압축 풀기
3. 안의 파일들을 저장소 최상단(root)에 업로드
4. Settings > Pages
5. Branch를 main, folder를 /root로 설정
6. 생성된 주소로 접속

Cloudflare Pages에 올릴 때:
1. Pages 프로젝트 생성
2. 이 ZIP 압축 푼 폴더를 업로드
3. Build command는 비워둠
4. Output directory는 / 또는 비워둠

주의:
- 저장 데이터는 같은 주소/같은 브라우저 기준으로 유지됩니다.
- 주소를 바꾸면 저장이 따로 잡힐 수 있으니, 저장 코드 복사/백업 파일 저장 기능을 같이 쓰세요.
- 새 버전을 올릴 때 service-worker.js의 CACHE_NAME을 바꾸면 캐시 갱신이 더 잘 됩니다.
