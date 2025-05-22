# Simple Landing Page

A simple landing page with a full-screen background image and a CTA button that automatically switches images based on the user's browser language.

## OG 이미지 설정

소셜 미디어 공유를 위한 OG 이미지를 추가하세요:

1. `og-image.jpg` 파일을 루트 디렉토리에 추가합니다.
2. 권장 이미지 크기: 1200 x 630 픽셀
3. 파일 크기: 8MB 미만

## 파비콘 설정

파비콘 파일을 추가하여 브라우저 탭에 아이콘을 표시하세요:

1. `favicon.ico` 파일을 루트 디렉토리에 추가합니다.
2. `apple-touch-icon.png` 파일을 iOS 기기용으로 추가합니다.

## 이미지 경로 설정

각 언어별 이미지는 다음 경로에 위치해야 합니다:
- English (en): `/images/enbackground.png`
- Japanese (ja): `/images/jabackground.png`
- Chinese Simplified (cn): `/images/cnbackground.png`
- Chinese Traditional (tw): `/images/twbackground.png`

## Setup Instructions

1. 각 언어별 이미지를 추가하세요. (`images/enbackground.png`, `images/jabackground.png` 등)
2. Customize the CTA button text and styling in `index.html` and `styles.css`.
3. Update the button link in `index.html` by changing the `href` attribute in the CTA button.

## GitHub Pages Setup

1. Push this repository to GitHub.
2. Go to your repository's Settings > Pages.
3. In the "Source" section, select "main" as your branch.
4. Click "Save" and GitHub will provide you with a URL for your page.

## Customization

- To change the button text, edit the text inside the `<a>` tag in `index.html`.
- To change the button color, edit the `background-color` property in the `.cta-button` class in `styles.css`.
- To adjust the button position, modify the `bottom` property in the `.cta-button-container` class in `styles.css`.
- 지원하는 언어를 변경하려면 `index.html`의 JavaScript 코드를 수정하세요. 