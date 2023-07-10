#Airbnb Django + Python ///////Comeback

1. poetry shell: shell 활성화를 위한 명령
2. django-admin
3. exit

#start project

1. poetry shell
2. python manage.py runserver
3. python manage.py migrate
4. python manage.py createsuperuser -> admin 계정생성
5. python manage.py startapp AAA
 #Model 내용 수정후 DB에 그사실을 알려줘야 한다. // 아래 2단계 매우 중요 !
6. python manage.py makemigrations  (migration 생성)
7. python manage.py migrate (migrate)  

Application: 데이터와 데이터의 로직이 있는 섬같은 개념.
models.py 어플리케이션에 있는 데이터의 정의나 설명을 적는 곳.
Django는 SQL데이터베이스 언어를 사용한다.(코드를 SQL로 자동 해석해준다.)
models생성 후에는 admin.py로 가서 생성한 model을 등록시켜야 한다.

- django-admin startproject config .
