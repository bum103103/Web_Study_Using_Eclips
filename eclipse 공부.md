# th란 무엇인가?

<strong th:text="&{id}">james</strong>님, 반갑습니다!! 
에서 쓰이는 th은 Thymeleaf의 속성 중 하나로, 이를 사용하여 HTML 요소의 텍스트 내용을 동적으로 설정할 수 있다.

# password와 text란 무엇인가?
spring에서 제공하는 기능으로 이해하면 편하다. 예를 들어서 비밀번호: <input type="password" name="password"> 라는 코드에서 앞의 password는 spring에서 제공하는 기능(검은 점으로 대체된다. 보안느낌?)이고, 뒤의 password는 변수명이다.

# 컨트롤러에 입력한다고만해서 되는건 아니다. html 소스 코드에   <form method="post" action="/ex02/answer"> 이런 코드를 작성해줘야 제대로 작동한다. 

<form method="post" action="/ex02/answer">

# answer 파일에서 계산이 필요할 경우?
Controller에 파일을 계산한 후 answer에 보내준다. 
