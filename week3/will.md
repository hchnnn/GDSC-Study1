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

- **장고**

    장고는 Model, Template, View 로 이름 붙여 MTV패턴이라고 부른다

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
-다음 시간까지 setting.py 앱 등록까지 진행하기




