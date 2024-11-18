# What I learned in week2

### MTV패턴이란? ###

- **아키텍쳐 패턴이란?**

    아키텍쳐 패턴이란 주어진 상황에서의 소프트웨어 아키텍쳐에서 
    일반적으로 발생하는 문제점들에 대한 일반화되고 재사용 가능한 솔루션임.

- **아키텍쳐 패턴의 장점**

    1. 유지보수성 향상
    2. 재사용성 증가
    3. 확장성 보장

- **MVC패턴**

    소프트웨어를 Model, View,Controller로 나누어 설계하는 방식
    Model은 데이터 입출력, View는 응답, 컨트롤러는 View와 Model의 전체적인 제어를 맡는다
    
    User: 사용자가 웹 사이트에 접속한다.
    Manipulates: Controller는 사용자가 요청한 웹 페이지를 보여주기 위해 Model을 호출한다.
    Updates: Model은 비즈니스 로직을 통해 DB 및 파일과 같은 데이터를 제어한 후 결과를 반환한다. 이후 Controller는 Model에게 반환받은 결과를 View에 반영한다.
    Sees: 데이터를 받아온 View가 사용자에게 웹 페이지를 출력하여 보여준다

    Model(모델)

- 데이터를 가지고 있으며, 데이터를 처리하는 로직 또한 가지고 있습니다.

​   View(뷰)

- 화면에 요청에 대한 결과물을 보여주는 역할을 합니다. 유저와 어플리케이션 간의 인터페이스 라고 생각할 수도 있습니다.

​   Controller(컨트롤러)

- 모델과 뷰를 이어주는 역할을 한다고 보시면 됩니다. 요청에 따라 모델에게 적절한 로직을 가동하도록 알려주고 모델이 응답하면 그 응답을 뷰에 전달하는 역할입니다.

- **장고**

    장고는 Model, Template, View 로 이름 붙여 MTV패턴이라고 부른다.

### 장고 프로젝트 구조 ###

- **장고 프로젝트 명령어**

    1. django-admin startproject
    2. django-admin startapp
    3. python manage.py runserver
    4. python manage.py makemigrations
    5. python manage.py migrate

- **프로젝트 VS 어플리케이션**

    1. 프로젝트: 우리가 장고로 만드는 소프트웨어 전체
    2. 어플리케이션: 프로젝트 내에서 기능 별로 쪼개놓은 단위

    하나의 프로젝트는 보통 여러 개의 어플리케이션으로 이루어져있다.

### 실습 ###
-다음 시간까지 setting.py 앱 등록까지 진행하기.




