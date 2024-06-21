# pycharm-oz-django-

Terminal tab 누르면 자동완성

poetry add -D black isort mypy django-stubs

poetry run black oz_django/asgi.py
읽기편하게 black 규칙에 맞추어 정리

Command shift 화살표 라인 끌고다닐 수 있음

Isort = import sort의 약자, import를 정렬해줌

Mypy = 정적분석을 위헤, 실행전 에러 감지

정적, 동적 : 실행 안해도 결과를 알 수 있으면 정적

터미널에서 mysql 설치
docker run --name ozdb -e MYSQL_ROOT_PASSWORD=1234 -e TZ='Asia/Seoul' -d -p 3306:3306 mysql:8.0.35

semver 1.2.3
1-major 2-minor 3-patch

