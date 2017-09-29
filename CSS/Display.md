---
# 가시 속성

<li> none : 화면에서 보이지 않게 만듬
<li> block : 태그를 block 형식으로 지정
<li> inline : 태그를 inline 형식으로 지정
<li> inline-bbloc : 태그를 inline block 형식으로 지정

```css
<style>
    #box{
        display: inline; /* 넓이 값과 무관하게 진행*/
        
        background-color: red;
        width: 300px;
        height: 50px;
        margin: 10px;
    }
</style>

<style>
    #box{
        display: inline-block; /* 넓이값을 초과하면 block 타입처럼 아래 새로 쓰여짐  */
        
        background-color: red;
        width: 300px;
        height: 50px;
        margin: 10px;
    }
</style>
```

---
# visibility 속성

<li> visible : 태그를 보이게 만듬
<li> hidden : 태그를 보이지 않게 만듬
<li> collapse : table 태그를 보이지 않게 만듬.

```css
<style>
    #box {
        visibility: hidden; /*보이지 않을 뿐, 자리는 차지*/
    }
    
    #box {
        display: none;      /*보이지 않고 사라*/
    }
</style>
```

---
# opacitiy 속성

```css
 <style>
    #checkbox{
        color:white;
        opacity: 0.2; /*투명도*/
    }
 </style>
```

