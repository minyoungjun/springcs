# Spring framework Cheat Sheet

> [Spring framework](https://spring.io/)를 공부하면서 헷갈리는 개념들 링크로 정리

### Servlet [내용 출처](https://mangkyu.tistory.com/14)

웹프로그래밍에서 클라이언트의 요청을 처리하고 그 결과를 다시 클라이언트에게 
전송하는 Servlet 클래스의 구현 규칙을 지킨 자바 프로그래밍 기술

#### CGI(Common Gateway Interface)란?

CGI는 특별한 라이브러리나 도구를 의미하는 것이 아니고, 별도로 제작된 웹서버와 프로그램간의 교환방식입니다. CGI방식은 어떠한 프로그래밍언어로도 구현이가능하며, 별도로 만들어 놓은 프로그램에 HTML의 Get or Post 방법으로 클라이언트의 데이터를 환경변수로 전달하고, 프로그램의 표준 출력 결과를 클라이언트에게 전송하는 것입니다.

즉, 자바 어플리케이션 코딩을 하듯 웹 브라우저용 출력 화면을 만드는 방법입니다.

