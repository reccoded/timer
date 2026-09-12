ON IT PWA v26.4

GitHub Pages 같은 HTTPS 정적 호스팅에 이 폴더 안 파일을 전부 같은 폴더에 올리면 됩니다.
메인 파일은 index.html 입니다.

포함 파일:
- index.html
- manifest.webmanifest
- sw.js
- icon-192.png
- icon-512.png
- icon-maskable-512.png

주의: Android는 백그라운드에서 페이지 JavaScript를 완전히 정지시킬 수 있으므로, 서버 푸시 없이 '정확한 시각'의 알림을 100% 보장할 수는 없습니다. 이 버전은 타이머 코드가 실행되는 동안 앱이 백그라운드/화면 꺼짐 상태일 때 서비스워커를 통해 OS 알림을 표시하도록 구성했습니다. 처음 타이머를 시작할 때 알림 권한 요청이 뜰 수 있습니다.
