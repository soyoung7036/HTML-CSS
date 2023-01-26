HTML 정리
=========
- atribute는 element의 추가적인 속성을 관리하는 역할이다   
- scr="" 이미지의 위치정보,URL를 받는다   
- h1~h6 글자크기별 제목   
- p 글자   
```
<p style="color:red;">i am red</p>
```
# CSS 사용법
head안에다가 style넣고 color-primary 지정
```
<style>
.color-primary{
    color:red;
}
</style>
```
p안에 넣기
```
<p class="color-primary">i am red</p>
```
<style>
.color-primary{
    color:red;
}
</style>

<p class="color-primary">i am red</p>
똑같이 빨간색인 i am red가 된다   
p안에 color-primary만 넣으면 한번에 컬러를 지정할 수 있다   
   
css링크만들기
------------
새파일에서 확장자명을 css로 style.css를 하나 만든다
style 엘리먼트를 지우고 
```
<link rel=stylesheet href=style.css>
```
를 넣어준다
```
<button type="button" onclick="javascript:alert('click button!');">Click</button>
```
