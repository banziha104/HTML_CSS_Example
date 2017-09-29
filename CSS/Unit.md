# 스타일시트 단위

<li> % : 백분율
<li> em : 배수 단위
<li> px : 픽셀

```css
p:nth-child(1){}
p:nth-child(2){font-size: 100%;}
p:nth-child(3){font-size: 150%;}
p:nth-child(4){font-size: 200%;}

p:nth-child(1){}
p:nth-child(2){font-size: 1.0em;}
p:nth-child(3){font-size: 1.5em;}
p:nth-child(4){font-size: 2.0em;}

p:nth-child(1){}
p:nth-child(2){font-size: 16px;}
p:nth-child(2){font-size: 32px;}
p:nth-child(2){font-size: 48px;}
```

---
# 색상단위

<li> #000000 : HEX 코드
<li> rgb(red,green,blue) : RGB 색상단위
<li> rgba(red,green,blue,alpha) : RGB 색상단위
<li> hsl(hue,saturation,lightness) : HSL 색상단위
<li> hsla(hue,saturation,lightness,alpha) : HSL 색상단위
<li> rgb(red,green,blue) : RGB 색상단위

---
# URL 단위

이미지나 폰트 파일을 불러올 때 사용

```css
<style>
    body{
        background-image: url('Desert.jpg');
    }
</style>
```
