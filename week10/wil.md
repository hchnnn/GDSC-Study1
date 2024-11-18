### http method와 ORM심화 ###

- **http method(복습)**

-해당 요청이 어떤 행동을 수행하는 메세지인지 전달하는 상태코드
-Http Request의 맨 앞에 나온다.


- ## 요청 분류 ##

-GET: 
1. 단순조회요청
2. 여러번요청해도결과동일
3. url에 정보를 넣어 전달해도됨
4. 캐싱가능

-POST:
1. 새로운리소스생성요청
2. 요청마다결과변경가능
3. 민감한정보를다룸
4. 캐싱불가능


- ## HTTP request ##

-Http Request
-목적지 : localhost:8000
-경로 : /questions/create
-정보 : subject=질문3

-start-line (시작 라인)
-header(헤더)
-empty-line (공백 라인)
-message-body(바디)

- ## http request사용 ##

-(예시) subject=request.Post['subject']


- ## ORM 심화 ##

- DB에 저장을 하고 싶을 때:객체를 만들어 값을 직접 저장한다.

- 수정: 일단 저장되어 있는 값을 가져온 다음 필요한 값을 수정하고 다시 저장해야한다.

- 삭제: 일단 저장되어 있는 값을 가져온 다음 delete() 메서드만 사용하면 된다.

- 검색:
  제목이 '질문 1' 인 질문만 가져오고 싶다면: questions=Question.objects.filter(subject='질문 1')

  - 제목에 '질문' 이 포함되어 있거나
    내용에 '질문'이 포함되어 있는 모든 질문 목록을 중복되지 않게 제공




