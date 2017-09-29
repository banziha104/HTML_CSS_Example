# overflow

overflowsms 부모의 범위를 벗어날 때 어떻게 처리할지 지정하는 속성

<li> hidden : 영역의 벗어나는 부분을 숨김
<li> scroll : 영역을 벗어나는 부분을 스크롤로 만듬

```css
body > div{
    width: 400px; height: 100px;
    border: 3px solid black;
    
    position: relative;
    overflow: hidden;
}
```