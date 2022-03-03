# Kyanon-Entrance-test
### Tính năng của API
**API 1 / SIGN-UP**: API cho phép người dùng mới sign-up vào hệ thống. 
**API 2 / SIGN-IN**: API cho phép người dùng (đã có trong hệ thống) sign-in vào hệ thống. 

**1. Cài đặt Django**
```python
python -m pip install Django
```

**2. Cài đặt Django Rest Framework**
```python
pip install djangorestframework
pip install django-rest-knox
```

**3. Thêm rest framework và knox**
```python
INSTALLED_APPS = [
    ...
    'rest_framework',
    'knox',
]
```
