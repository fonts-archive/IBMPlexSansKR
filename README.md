# IBM Plex Sans KR

[배포처 바로가기](https://github.com/IBM/plex)

&nbsp;

## 웹 폰트

사용하는 `font-family`의 이름은 `IBM Plex Sans KR`입니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR.css" type="text/css"/>
```

### CSS `@Import`

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR.css');
```

### CSS `@font-face`

```css
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 100;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Thin.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Thin.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Thin.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Thin.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 200;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-ExtraLight.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 300;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Light.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Light.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Light.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Light.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 400;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Regular.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Regular.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Regular.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Regular.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 500;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Medium.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Medium.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Medium.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Medium.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 600;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-SemiBold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-SemiBold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-SemiBold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-SemiBold.ttf') format('truetype');
}
@font-face {
    font-family: 'IBM Plex Sans KR';
    font-weight: 700;
    font-style: normal;
    font-display: swap;
    src: url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Bold.woff2') format('woff2'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Bold.woff') format('woff'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Bold.otf') format('opentype'),
         url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/IBMPlexSansKR-Bold.ttf') format('truetype');
}
```

&nbsp;

## 다이나믹 서브셋

웹폰트의 최적화를 위해 모던 브라우저에서는 글리프를 여러개로 나누어 필요한 부분만 동적으로 파싱하는 다이나믹 서브셋을 제공합니다. 폰트의 용량이 부담된다면 아래 코드를 사용하는 걸 추천합니다.

### HTML

```html
<link rel="stylesheet" href="https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/subsets/IBMPlexSansKR-dynamic-subset.css" type="text/css"/>
```

### CSS

```css
@import url('https://cdn.jsdelivr.net/gh/fonts-archive/IBMPlexSansKR/subsets/IBMPlexSansKR-dynamic-subset.css');
```

&nbsp;

## font-family

어느 브라우저나 시스템 환경에서도 동일한 폰트가 적용되어야 한다면 아래와 같이 구성하는 걸 추천합니다. `-apple-system`과 `BlinkMacSystemFont`는 맥, `Segoe UI`는 윈도우, `Roboto`는 안드로이드의 기본 폰트입니다.


```css
font-family: "IBM Plex Sans KR", -apple-system, BlinkMacSystemFont, "Segoe UI", Roboto, Oxygen, Ubuntu, Cantarell, "Open Sans", "Helvetica Neue", sans-serif;
```

&nbsp;

## 라이선스

라이선스는 언제든지 변경될 수 있습니다. 변경사항을 확인하려면 배포처를 방문해 주세요.

```
Copyright © 2017 IBM Corp. with Reserved Font Name "Plex"  

This Font Software is licensed under the SIL Open Font License, Version 1.1. 
This license is copied below, and is also available with a FAQ at: 
http://scripts.sil.org/OFL  

----------------------------------------------------------- 
SIL OPEN FONT LICENSE Version 1.1 - 26 February 2007 
-----------------------------------------------------------  

라이선스 전문 보기(영어)
라이선스 전문 보기(한글)
```
