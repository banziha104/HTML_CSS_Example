# Position

<li> 절대 위치 좌표 : X와 Y축을 이용해 지정
<li> 상대 위치 좌표 : 요소를 입력한 순서를 통해 상대적으로 위치를 지정

```css
.red{
    position: absolute;
}
```

<li> static : 태그가 위에서 아래 순서로 배치
<li> relative : 초기 위치 상태에서 위치를 이동
<li> absoulte : 절대 위치 좌표를 설정
<li> fixed : 화면을 기준으로 절대 위치 좌표를 설정함.

---
# Z-index

올라오는 것의 순서를 주고 싶은 경우

```css
.upbox{
    z-index: 10;
}

.downbox{
    z-index: 20; /*downbox가 올라오게됨*/
}
```

---
# 위치와 과련된 공식

position 속성에 absoulte 키워드를 적용하면 부모 태그가 영역을 차지하지 않음
