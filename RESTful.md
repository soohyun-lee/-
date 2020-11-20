## RESTful API

* REST : Respresentational State Transfer(대표적인 상태 전달)
  * RESTful API는 REST라는 아키텍처를 구현하는 웹 서비스를 나타내기 위해 사용하는 용어이며 REST원리를 따르는 시스템이다

  - 월드 와이드 웹과 같은 분산 하이퍼미디어 시스템을 위한 소프트웨어 개발 아키텍처의 한 형식
    - 웹의 기존 기술과 HTTP 프로토콜을 그대로 활용하기 때문에 웹의 장점을 최대한 활용할 수 있는 형식
    - Client와 Server 사이의 통신 방식 중 하나
  
  - 구체적인 개념
    - HTTP URI (Uniform Resource Identifier)를 통해 자원(resource)를 명시하고, HTTP 메소드(Post, Get, Put, Delete)를 통해 해당 자원에 대한 CRUD Operation을 적용하는 것을 의미
    - 웹 사이트의 이미지, 텍스트, DB 내용 등의 모든 자원에 고유 ID인 HTTP URI를 부여한다.
    
  - 장점
    - Open API를 제공하기 쉽다.
    - 하이퍼미디어 지원 및 연동이 용이하다.
    - 원하는 타입으로 데이터를 주고 받을 수 있다.
    - 기존 웹 인프라(HTTP)를 그대로 사용 할 수 있다.
    
  - 단점
    - 메소드 4개만 사용 가능
    - 분산환경에는 부적합
    - 구형 브라우저는 지원하지 못하는 부분 존재(PUT, DELETE 사용 못함)
  
  - 그럼에도 필요한 이유
    - 애플리케이션 분리 및 통합
    - 최근의 서버 프로그램은 다양한 브라우저, 핸드폰(아이폰, 안드로이드) 와 같은 여러 디바이스에서도 통신 할 수 있어야 한다.
    
   
  * REST 구성 요소 ( 자원 / 행위 / 표현 )
    1. 자원(Resource): URI
      - 모든 자원에 부여된 고유한 ID
      - 클라이언트는 URI를 이용해 자원을 지정하고, 해당 자원의 상태에 대한 조작을 서버에 요청
    
    2. 행위 : HTTP MEthod
      - GET, POST, PUT, DELETE, HEAD와 같은 메서드
      
    3. 표현
      - 클라이언트의 요청에 해당하는 응답을 보낸다.
      - JSON, XML, TEXT, RSS 등 여러 형태 (주로 JSON, XML)
    
참조 : [참조링크][참조link]

[참조link]: https://github.com/WeareSoft/tech-interview/blob/master/contents/network.md#rest%EC%99%80-restful%EC%9D%98-%EA%B0%9C%EB%85%90
