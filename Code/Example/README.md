
----
## HTML
----

### 기본 태그
-----
```html
 <!DOCTYPE html> <!-- 문서 유형을 html로 지정-->
<html lang="ko"> <!-- 문서의 언어를 설정 & 웹 문서의 시작을 알림-->
<head> <!--웹브라우저 화면에는 보이지 않지만, 정보들을 담는 부분-->
    <meta charset="UTF-8"> <!--문자 인코딩 및 문서 키워드, 요약 정보
                               검색 엔진에 문서 정보를 알리는 역활도 함-->
    <title>Title</title> <!--문서 제목-->
</head>
<body> <!--실제 브라우저에 표시될 내용-->
 <h1>제목 표시하기</h1> <!--html문서의 제목을 표시 h1이 가장큼-->
 <p>단락 만들기</p>     <!--단락 만들기-->
 <p>줄 바꾸기 <br>      <!--<br>줄바꿈-->
    다음 줄</p>
 <p>분위기 전환하기</p>
 <hr>                  <!--hr 분위기 전환-->
 <p>분위기 전환</p>
 <blockquote>인용문넣기</blockquote> <!--인용문 넣기-->
 <pre>입력하는 그 대 로  화면에 출력하기</pre> <!--공백 또한 그대로 표시-->
</body>
</html>
```
![example1](https://github.com/banziha104/HTML_CSS_Example/blob/master/example1.jpg)

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
<strong>강조할 태그<br></strong> <!--강조할 태그-->
<b>굵게 표시할 태그<br></b>      <!--굵게 표시할 태그-->
<i>이탤릭체로 표시할 텍스트<br></i> <!--이탤릭체로 표시하는 태그-->
<em>이탤릭체로 강조할 텍스트<br></em><!--이탤릭체로 강조하는 태그-->
<h1>인용 제목<br></h1>
<q>인용 부분 표시하기</q><br> <!--인용 부분 표시하기-->
<mark>형광펜 효과 내기</mark> <!--형광펜 효과 내기-->
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
     <li> 목록1 </li>       <!--목록 만들기 </li>는 생략 가능-->
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
<img src="htmlTag1.png">                         <!--이미지 불러오기-->
<img src="htmlTag1.png" alt="홈으로 가기"/>       <!--alt 속성 이미지를 설명해주는 텍스트-->
<img src="htmlTag1.png" width="200" height="120"><!--이미지 크기 조정-->
<figure>                                         <!--설명 글을 붙일 대상 지정-->
    <img src="htmlTag1.png">
    <figcaption>설명부분</figcaption>             <!--설명 글 붙이기-->
</figure>

</body>
</html>
```

-----
### 링크
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<a href="http://www.github.com/banziha104">깃허브 주소</a>      <!--링크 걸기-->
<a href="http://www.github.com/banziha104">
    <img src="htmlTag1.png">                                   <!--이미지 링크 걸기-->
</a>
<a href="http://www.github.com/banziha104" target="_blank"></a><!-- target 속성 새창에서 열기-->
<a href="#content1">앵커</a>                                    <!--앵커, 한 문서 내에서 이동하는
                                                                    하이퍼 링크-->
<h2 id="content1">첫번째</h2>

</body>
</html>
```

-----
### Form 태그
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<fieldset>
    <legend>폼 요소 그룹 제목</legend>  <!--폼요소를 그룹으로 묶음 fieldset과 같이 사용-->
    <form action="server.js" method="get">  <!--action 처리할 서버상 프로그램 지정
                                            method 어떻게 넘겨줄지 지정-->
        <input type="text" title="검색"/>   <!---->
        <label id="label">                  <!--폼 요소에 레이블 붙이는 첫번째 방법-->
            <input type="submit" value="검색"/>
        </label>
        <label for="input_id">두번째</label><!--폼 요소에 레이블 붙이는 두번째 방법-->
        <input id="input_id" type="text">
    </form>
</fieldset>

</body>
</html>
```
-----
### Input 타입
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<form action="server.js" method="get">
    <label>hidden<input type="hidden" name="이름" value="값"><br></label>  <!--히든 필드 만들기-->
    <label>id    <input type="text"   id="user_id">  <br></label>          <!--텍스트 입력란 -->
    <label>ps    <input type="password" id="password"> <br></label>        <!--패스워드 입력란-->
    <label>search<input type="search" id="search"><br></label>             <!--검색 상자-->
    <label>url   <input type="url" id="url"><br></label>                   <!--url 입력란(http로시작)-->
    <label>email <input type="email" id="email"><br></label>               <!--email 입력란-->
    <label>tel   <input type="tel" id="tel"><br></label>                   <!--전화번호 입력란-->
    <label>number<input type="number" id="number"><br></label>             <!--숫자 입력란-->
    <label>range <input type="range" id="range"> <br></label>              <!--길이가 있는 입력-->
    <label>radio <input type="radio" id="radio"> <br></label>              <!--라디오 버튼-->
    <label>check <input type="checkbox" id="checkbox"> <br></label>        <!--체크 박스-->
    <label>color <input type="color" id="color"> <br></label>              <!--컬러 고르기-->
    <label>date  <input type="date" id="date"> <br></label>                <!--날짜 입력-->
    <label>submit<input type="submit" id="submit"><br> </label>            <!--전송-->
    <label>reset <input type="reset" id="reset"><br> </label>              <!--초기화-->
    <label>image <input type="image" id="image"><br> </label>              <!--이미지삽입-->
    <label>button<input type="button" id="button"><br> </label>            <!--버튼-->
    <label>file <input type="file" id="file"><br> </label>                 <!--파일 삽입-->
</form>
</body>
</html>
```

-----
### Input 속성
----
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <title>Title</title>
</head>
<body>
<form id="ab" action="Example1.html" method="get">
    <label><input type="text" autofocus required></label> <!--열림과 동시에 포커싱 됌-->
    <label><input type="text" placeholder="힌트"></label> <!--힌트 주기-->
    <label><input type="text" readonly></label>           <!--읽기만 가능-->
    <label><input type="text" required></label>           <!--필수 필드 지정-->
    <label><input type="text" min="10" max="12"></label>  <!--최솟값과 최대값 지정-->
    <label><input type="text" size="10" ></label>         <!--몇 글자를 보이게 할지 지정-->
    <label><input type="text" minlength="10" maxlength="5"></label> <!--글자 길이 제한-->
</form>
</body>
</html>
```
