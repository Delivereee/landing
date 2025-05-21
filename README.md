# Simple Landing Page

A simple landing page with a full-screen background image and a CTA button that automatically switches images based on the user's browser language.

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
- 지원하는 언어를 변경하려면 `index.html`의 `supportedLanguages` 배열을 수정하세요. 