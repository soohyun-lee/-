## TDD 란 무엇인가?
* Tett-Driven Development(TDD)는 아주 짧은 개발 사이클의 반복에 의존하는 소프트웨어 개발 프로세스
* 즉, 테스트 코드가 작성을 주도하는 개발 방식
* 좋은 점
  * 코드량이 방대해지면 리팩토링을 하게 된다(로직 수정, 확장성 고려, 변수명/클래스명 일관성)
  * 이때, 테스트 주도 개발을 통해 개발을 해왔다면 테스트 코드가 그 중심을 잡아 줄 수 있다

## 함수형 프로그래밍
 * immutable vs mutable
  - immutable
    : 객체는 객체가 가지고 있는 값을 변경할 수 없으며, 값이 변경될 경우 새로운 객체를 생성하고 변경된 값을 주입하여 반환해야 한다.
  - first-citizen
    : 할당에 사용된 이름과 관계없이 고유한 구별이 가능하다
    : 함수를 리터럴로 바로 정의할 수 있다
    
    
## CORS란 ?
 * CORS (Corss Origin Resouce Sharing)
    - 웹 서버에게 보안 cross-domain 데이터 전송을 활성화 화는 cross-domain 접근 제어권을 부여
   
 * 배경
    - 처음 전송되는 리소스의 도메인과 다른 도메인으로부터 리소스가 요청 될 경우 해당 리소스는 cross-origin HTTP 요청에 의해 요청된다.
    - 보안 상의 이유로 브라우저들은 스크립트 내에서 초기화 되는 cross-origin HTTP 요청을 제안한다
 
 * 과정
    - CORS 요청 시에는 미리 OPRIONS 주소로 서버가 cors를 허용하는지 물어본다
    - 이때 Access-Control-Request-Method 로 실제로 보내고자 하는 메소드를 알리고
    - Access-Control-Request-Headers 로 실제로 보내고자 하는 헤더들을 알림
    - Allow 항목들은 request에 대응되는 것으로, 서버가 허용하는 메서드와 헤더를 응답하는데 사용됨
    - Request랑 Allow가 일치하면 CORS 요청이 이루어 진다.
