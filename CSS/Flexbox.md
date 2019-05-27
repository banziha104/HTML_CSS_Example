# Flexbox

- flextbox 는 Parent(flex-container)를 Child(flex-item)을 컨트롤
- justfiy-content
    - space-between : 동일한 간격으로 나누어줌
    - space-arround : between과 비슷한데 양옆으로 여백이있음
    - flex-start : 시작하는 지점으로 몰아줌
    - flex-end : 끝지점으로 몰아줌 
    - flex-warp : 기본적으로 flex는 윈도우가 줄어들면 같이 줄어드는데, wrap을 사용하면 크기가 고정됨 (더 이상 공간이 존재하지 않을 때의 행동을 규정)
    - flex-direction : 순서를 정해줌
    - align-self : 컨테이너가 아닌 해당 컨텐츠에게 직접 달
- axis 
    - justify-content : main axis
    

```css
/* 동일한 간격으로 띄워주는 예제*/
        body{
            display : flex;
            justify-content: space-between;
        }

        .box{
            width : 200px;
            height: 200px;
            background-color: blue;
        }

``` 

