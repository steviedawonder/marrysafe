# 메리세이프 현장 매뉴얼 — 웹 배포본

`index.html` 한 파일이 전부입니다. 폰트와 사진이 내장되어 있어 외부 요청이 없고,
한 번 열어 두면 네트워크가 끊겨도 읽힙니다.

- 배포: main 브랜치에 푸시하면 Actions가 GitHub Pages로 올립니다.
- 검색 차단: `robots.txt`와 `<meta name="robots" content="noindex">`로 검색엔진에 노출되지 않습니다.
  링크를 아는 사람은 볼 수 있으므로 **비밀번호가 필요하면 별도 조치가 필요합니다.**
- 원본: 비공개 저장소 `steviedawonder/marrysafe_guide`의 `guide/marrysafe-field-manual.html`.
  이 폴더의 index.html은 거기서 생성된 배포본이므로 **여기서 직접 고치지 마세요.**
