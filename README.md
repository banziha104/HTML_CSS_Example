
----
## HTML
----

### 텍스트를 한 줄로 표시하는 태그
-----
```html
 <!DOCTYPE html>                     <!-- 문서 유형을 html로 지정-->
<html lang="ko">                     <!-- 문서의 언어를 설정 & 웹 문서의 시작을 알림-->
<head>                               <!--웹브라우저 화면에는 보이지 않지만, 정보들을 담는 부분-->
    <meta charset="UTF-8">           <!--문자 인코딩 및 문서 키워드, 요약 정보
                                         검색 엔진에 문서 정보를 알리는 역활도 함-->
    <title>Title</title>             <!--문서 제목-->
</head>
<body>                                 <!--실제 브라우저에 표시될 내용-->
 <h1>제목 표시하기</h1>                   <!--html문서의 제목을 표시 h1이 가장큼-->
 <p>단락 만들기</p>                       <!--단락 만들기-->
 <p>줄 바꾸기 <br>                       <!--<br>줄바꿈-->
    다음 줄</p>
 <p>분위기 전환하기</p>
 <hr>                                  <!--hr 분위기 전환-->
 <p>분위기 전환</p>
 <blockquote>인용문넣기</blockquote>      <!--인용문 넣기-->
 <pre>입력하는 그 대 로  화면에 출력하기</pre> <!--공백 또한 그대로 표시-->
</body>
</html>
```

-----
### 텍스트를 한 줄로 표시하는 태그
----
```html
<!DOCTYPE html>
<html lang="ko">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<strong>강조할 태그<br></strong>    <!--강조할 태그-->
<b>굵게 표시할 태그<br></b>          <!--굵게 표시할 태그-->
<i>이탤릭체로 표시할 텍스트<br></i>    <!--이탤릭체로 표시하는 태그-->
<em>이탤릭체로 강조할 텍스트<br></em>  <!--이탤릭체로 강조하는 태그-->
<h1>인용 제목<br></h1>
<q>인용 부분 표시하기</q><br>         <!--인용 부분 표시하기-->
<mark>형광펜 효과 내기</mark>        <!--형광펜 효과 내기-->
</body>
</html>
```
-----
### 목록을 만드는 태그
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
 <ul>                       <!--순서가 필요하지 않은 목록 만들기-->
     <li> 목록1 </li>        <!--목록 만들기 </li>는 생략 가능-->
     <li> 목록2 </li>
     <li> 목록3 </li>
 </ul>
<ol type="1">               <!--순서가 필요한 목록 type 지정가능 -->
                            <!--1:숫자, a:알파벳 소문자,A:알파벳 대문자-->
    <li>내용1</li>
    <li>내용2</li>
    <li>내용</li>
</ol>
<dl>                        <!--설명 목록 만들기-->
    <dt>제목</dt>
    <dd>내용</dd>
    <dt>제목2</dt>
    <dd>내용</dd>
</dl>
</body>
</html>
```

-----
### 표를 만드는 태그
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<table border="2">              <!--표자리 만들기-->
    <caption>                   <!--표에 제목 붙이기 <figcaption>의 경우 왼쪽으로 정렬됌-->
        <p>표에 제목 붙이기</p>
    </caption>
    <tr>
        <th>제목</th>           <!--표에 제목 셀 만들기-->
        <td>1행 2열</td>        <!--표에 셀 넣기 만들기-->
        <td>1행 3열</td>
    </tr>
    <tr>
        <th>제목</th>
        <td colspan="2"></td>   <!--셀 합치기-->
    </tr>
</table>
</body>
</html>
```

-----
### 이미지 넣기 태그
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<img src="htmlTag1.png">                          <!--이미지 불러오기-->
<img src="htmlTag1.png" alt="홈으로 가기"/>          <!--alt 속성 이미지를 설명해주는 텍스트-->
<img src="htmlTag1.png" width="200" height="120"> <!--이미지 크기 조정-->
<figure>                                          <!--설명 글을 붙일 대상 지정-->
    <img src="htmlTag1.png">
    <figcaption>설명부분</figcaption>               <!--설명 글 붙이기-->
</figure>

</body>
</html>
```
