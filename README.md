# hello idon

---
1. startproject
   1. pip install django~=3.2
   2. django-admin startproject _helloidol ._
   3. python manage.py runserver
2. startapp _playground_
   1. Terminal
      1. python manage.py startapp **playground**
   2. _helloidon_/settings.py
      1. 'playground', in INSTALLED_APPS
3. playground/
   - 정보 전달: urls -> views -> (models -> ) -> templates
   - 코드 작성: (models -> ) views -> templates -> urls
   1. views
      1. say_hello()