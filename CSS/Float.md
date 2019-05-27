# float

<li> left: 태그를 왼쪽에 붙임
<li> right : 태그를 오른쪽에 붙임

```html
<body>
    <div class="box">1</div>
    <div class="box">2</div>
</body>
```

```css
.box{
    width: 100px; height: 100px;
    background-color: coral;
    float : left; /*1번박스부터 왼쪽에 붙음*/
    /*float: right; 1번박스부터 오른쪽에 붙음*/
}
```

<li> One True Layout : 자손에 float 속성을 적용하면 부모에 overflow 속성에 hidden을 적용한다

