# width와 height

```css
# box{
    width: 100px; /* 가로 값 */
    height: 100px; /* 세로 값 */
}
```

---
# margin과 padding

<li> margin : border를 중심으로 외각의 여분
<li> padding : border를 중심으로 내각의 여분

---
# box-sizing 
 
<li> content-box : default 값
<li> border-box : border를 기준으로 width와 height를 기준으로함.

```css
div:first-child{
    background:red;
    box-sizing: border-box;
}

div:last-child{
    background-color: coral;
    box-sizing: content-box;
}
```