主要环境：

- PowerDesigner
- MySQL Workbench 8.0 CE
- Python 3.8
- Django 3.2.8
- BootStrap 3.3.7
- Django-simpleui

1. 项目启动，进入项目 `django_CCOS` 目录，执行：
   - `python manage.py makemigrations`
   - `python manage.py migrate`
   - `python manage.py runserver`
   
2. 前端访问：http://127.0.0.1:8000

3. 后台访问：http://127.0.0.1:8000/admin
   - 创建管理员：`python manage.py createsuperuser`
   - 自行添加食堂、窗口、菜品，否则初始不显示

