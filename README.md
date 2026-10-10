# push-images

원시그널 푸시 썸네일 보관용 저장소.

- `images/<업로드 날짜>/파일.jpg` 로 올림
- 주소: `https://raw.githubusercontent.com/okcallpang-gif/push-images/main/images/<날짜>/<파일>.jpg`
- 매일 03:00(KST) GitHub Actions(`cleanup-old-images`)가 업로드 30일 지난 날짜 폴더를 지움
