## HTTP


  1. 의미
    1 Hyper Text Transfer Protocol
    2 Hyper Text: 참조를 통해 한 문서에서 관련된 다른 문서들로 넘나들며 원하는 정보를 얻을 수 있게 해주는 텍스트
    3 Transfer protocol: 인터넷을 통해 정보를 주고받을 때 지켜야 되는 규칙
  2. 구성
    1 Request
    2 Response
  3. 요청 메소드
    1 GET: URL에 표시된 리소스를 가져오기
    2 POST : 댓글을 달거나 글 게시. BODY에 정보 담아서 서버에 입력
    3 PUT : URL에 표시된 리소스와 바꿔 치기
    4 PATCH : 일부만 수정(PUT과 다른 점)
    5 DELETE: URL에 표시된 특정 리소스 삭제
    
    
 ## JSON
  1. 의미
    1 Java Script Object Notation (JSON)
    2 Key : Value 형식을 가짐. (Python의 딕셔너리와 유사)
    3 데이터 교환
  2. 특징
    1 기존 XML보다 가볍다
    2 많은 프로그래밍 언어가 지원한다
    3 전송 시: 직렬화 과정을 거친다
    4 수신 시: 역직렬화 과정을 거친다
  3. JSON 형식 예시
    1 MDN JSON 문서 : https://developer.mozilla.org/ko/docs/Learn/JavaScript/Objects/JSON
    2 같은 페이지의 Superhero data : https://mdn.github.io/learning-area/javascript/oojs/json/superheroes.json


## API
 1. 의미
   1 Application Programming Interface(API)
   2 Application의 Programming Interface 제공
     1 우리가 사용하는 다양한 서비스들이 제공해주는 데이터들에 접근하고 사용할 수 있도록 도와주는 도구
     2 TV의 리모컨 같은 존재다
 2. 종류
   1 SOAP: Simple Object Access Protocol
   2 REST Representational State Transfer
     1 REpresentational State Transfer
     2 하나의 아키텍쳐 (지침과 원칙 부여)
     3 REST의 구성요소
       1 자원
       2 행위
       3 표현
   3 GraphQL: Graph Query Language
