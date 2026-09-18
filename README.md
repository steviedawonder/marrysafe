# 메리세이프 현장 매뉴얼 — 웹 배포본

공개 주소: **https://steviedawonder.github.io/marrysafe/**

`index.html` 한 파일이 전부입니다. 폰트와 사진이 내장되어 있어 외부 요청이 없고,
한 번 열어 두면 네트워크가 끊겨도 읽힙니다.

## 갱신 방법

`guide/marrysafe-field-manual.html` 을 고친 뒤:

```bash
bash tools/deploy-web.sh
```

배포본을 새로 만들고 공개 저장소 `steviedawonder/marrysafe` 의 `gh-pages` 브랜치로
푸시한 뒤, 실제 주소에 반영됐는지까지 확인합니다.

**이 폴더의 index.html 을 직접 고치지 마세요.** 원본은 `guide/marrysafe-field-manual.html` 입니다.

## 노출 범위

`robots.txt` 와 `<meta name="robots" content="noindex">` 로 검색엔진에는 잡히지 않습니다.
다만 **주소를 아는 사람은 누구나 열 수 있습니다.** 비밀번호는 걸려 있지 않습니다.
