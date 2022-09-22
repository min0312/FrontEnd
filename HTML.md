# FrontEnd
## git 설정
### 2022.09.19.
1. git 명령 정리
+ git add .
+ git commit -m "내용"
+ git push origin master


## HTML
### 2022.09.20.
1. 태그(tag)
+ 표준 : https://html.spec.whatwg.org/multipage/
+ 참고 사이트
  + https://www.w3schools.com/
  + https://developer.mozilla.org/ko/docs/Web/HTML
  + https://emmet.io/
2. HTML 기본구조
+ !DOCTYPE html> : 문서를 선언하는 태그
+ html> : HTML 문서의 시작과 끝을 의미. 모든 HTML 태그들은 안쪽에 입력
+ title> : 웹사이트 탭에 나타나는 제목을 적는 태그
+ head>
+ body>
3. 주석
+ < !-- -->
4. 태그
+ h> : h1>~h6>, 제목이나 부제목 표현, 숫자 값이 클수록 폰트 사이즈가 작음
+ p> : 본문 내용
+ ol> : 순서가 있는 리스트 생성
+ ul> : 순서가 없는 리스트 생성. 메뉴 버튼 만들 때 사용
+ li> : 위 항목 나열할 때 사용
+ a> : 글자나 이미지 클릭시 다른 사이트로 이동, 열린태그와 닫힌 태그 사이에 컨텐츠 입력
+ href 속성 : HTML 연결할 페이지 주소 지정
+ img> : 정보성을 갖고 있는 이미지를 삽입. 닫힌 태그 없음
  + img 상대경로 : .(현재위치)/폴더명/파일명.확장자
  + -> 절대경로 사용하지 말것
+ src 속성 : 삽입할 이미지 파일 경로
- a href="#">img src="#">/a>


### 2022.09.21.
#### 시맨틱 웹
+ 검색엔진에 잘 노출될 수 있도록 만드는 웹
  + 참고 : https://developers.google.com/search/docs

#### emmet 문법
1. div#id$*개수
+ -> div id="id1"> /div> 
2. (div.dvc$>h1+ul>li.lic$)*개수 
+ -> div class="dvc1">
    h1>/h1>
    ul>
      li class="lic1">/li>
    /ul>
  /div>
3. div.class$*개수
+ -> div class="class1">/div>

#### 기타
+ . : class
+ " # " : id
+ a href 링크 시 같은 페이지는 #클래스명