# 다국어 배경 이미지 설정

각 언어별 배경 이미지를 다음 경로에 저장해야 합니다:

- 영어(en): `images/en/background.jpg`
- 일본어(ja): `images/ja/background.jpg`
- 중국어 간체(cn): `images/cn/background.jpg`
- 중국어 번체(tw): `images/tw/background.jpg`

## 이미지 요구사항

- 모든 이미지는 동일한 이름(`background.jpg`)으로 저장해야 합니다.
- 이미지 크기는 최소 1920x1080px 이상을 권장합니다.
- 웹 최적화를 위해 이미지 크기는 2MB 이하로 유지하는 것이 좋습니다.

## 다른 파일 형식 사용 방법

다른 파일 형식(예: .png, .webp)을 사용하려면:
1. `index.html` 파일에서 JavaScript 코드의 `container.style.backgroundImage` 부분을 수정하세요:
   ```javascript
   container.style.backgroundImage = `url('images/${userLang}/background.png')`;
   ``` 