할일장부 PWA - 무료 호스팅 방법 (GitHub Pages)
================================================

이 폴더 안의 파일 6개(index.html, manifest.json, service-worker.js,
icon-192.png, icon-512.png, icon-512-maskable.png)를 그대로 올리면 돼요.
전부 무료입니다.

1) GitHub 계정 만들기
   https://github.com 에서 가입 (이미 있으면 생략)

2) 새 저장소(repository) 만들기
   - 오른쪽 위 [+] 버튼 -> New repository
   - Repository name: checklist-app (원하는 이름으로 가능)
   - Public 선택 -> Create repository

3) 파일 업로드
   - 방금 만든 저장소 페이지에서 "uploading an existing file" 클릭
   - 이 폴더의 파일 6개를 전부 끌어다 놓기 (드래그 앤 드롭)
   - 아래 Commit changes 버튼 클릭

4) GitHub Pages 켜기
   - 저장소 상단 메뉴 Settings 클릭
   - 왼쪽 메뉴에서 Pages 클릭
   - Branch를 "main" (또는 "master"), 폴더는 "/ (root)" 선택 후 Save

5) 몇 분 기다리면 주소가 생겨요
   https://내깃허브아이디.github.io/checklist-app/
   (Settings > Pages 화면에 정확한 주소가 표시돼요)

6) 핸드폰에서 설치
   - 안드로이드 크롬으로 위 주소 접속
   - 오른쪽 위 ⋮ 메뉴 -> "앱 설치" 또는 "홈 화면에 추가" 선택
   - 진짜 앱처럼 아이콘이 생기고, 주소창 없이 전체화면으로 열려요
   - 인터넷이 없어도 한 번 열었던 화면은 오프라인에서도 열립니다

참고
----
- 데이터(체크 기록)는 각 사용자 핸드폰 브라우저(localStorage)에 저장돼요.
  즉 내 폰에만 저장되고, 기기를 바꾸면 기록이 이어지지 않아요.
- 나중에 진짜 .apk 파일까지 원하시면, 위 GitHub Pages 주소를
  https://www.pwabuilder.com 에 입력하면 무료로 apk를 만들어주는
  빌드 도구를 사용할 수 있어요 (Google Play 등록 없이 apk 파일만 받는 것도 가능).

