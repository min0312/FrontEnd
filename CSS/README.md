# FrontEnd
## CSS

### 참고사이트 
+ https://www.photopea.com/
+ https://colorhunt.co/


### 22.09.21
#### CSS 구성
+ 선택자 : {}
+ 선언 : 속성 : 값;

#### CSS 선택자 
+ " * " : 전체 선택자
+ 태그명 : 태그 선택자
+ class : .클래스명 으로 호출, 그룹화 시킴, 같은 이름으로 여러개면 그룹화됨
+ id : #아이디명 으로 호출, 제각각. only one
+ 태그[속성] / 태그[속성=값] : 속성 선택자
+ 부모 안 자식을 찾을 시 " 부모 > 자식 "
+ 여러개 동시에 " , " 로 묶기
1. 가상 클래스 셀렉터
  + 선택자:hover : 마우스가 올라가 있을 때
  + 선택자:link : 방문하지 않은 링크일 때
  + 선택자:visited : 방문한 링크일 때

#### 박스 모델
1. 박스 모델 영역 : 가로/세로 길이 제어 가능
  + 콘텐츠 영역
  + 안쪽 여백 영역(padding)
  + 테두리 영역(border)
  + 바깥 여백 영역(margin) : margin: 20px, 10px, 30px, 50px;
    -> top right bottom left(시계방향)


#### div 와 span 의 차이
+ DIV 태그는 사각형 박스 모양으로 구역을 지정
+ SPAN은 한 문장 단위
+ 둘은 매우 유사하나 span 태그는 인라인 요소이기 때문에 w/h 적용 불가함



### 22.09.22
####
+ display: flex // 가로로 정렬
+ display: box // 세로로 정렬
+ justify-content: space-between // 공간 맞춰서 전체적 정렬

+ https://noonnu.cc/font_page?commit=filter&search=&search=&editor=&category_style_ids%5B%5D=1&order_by=pd


+ % / em, rem / vh, vw 권장
