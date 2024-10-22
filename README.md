# Y유니버스체

[배포처 바로가기](https://www.yspotlight.co.kr/brand/font?tabNo=2)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `YUniverse`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse.css');
```

### CSS `@font-face`

```css
@font-face {
  font-family: 'YUniverse';
  font-weight: 300;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Light.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Light.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Light.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Light.ttf') format('truetype');
}
@font-face {
  font-family: 'YUniverse';
  font-weight: 700;
  font-style: normal;
  font-display: swap;
  src: url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Bold.woff2') format('woff2'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Bold.woff') format('woff'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Bold.otf') format('opentype'),
        url('https://cdn.jsdelivr.net/gh/fonts-archive/YUniverse/YUniverse-Bold.ttf') format('truetype');
}
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.

```css
font-family: "YUniverse", -apple-system, BlinkMacSystemFont, "Segoe UI",Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
• Y유니버스체의 지식재산권은 |주|케이티에 있다. 
• Y유니버스체는 개인 및 기업 사용자를 포함한 모든 사용자에게 무료로 제공되며, 폰트 사용자에 의한 재배포 또한 가능하다. 단, 폰트 파일의 수정 및 유료 판매는 금지한다. 
• Y유니버스체는 인쇄, 웹, 영상, 임베딩, 패키지 등에 상업적 목적으로 사용이 가능하다. 단, BI/CI 용도로는 사용을 금지한다.
```
